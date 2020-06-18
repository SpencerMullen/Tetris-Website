# Tetris-Website

A simple tetris website with singleplayer and multiplayer features

Project Created by Spencer Mullen, Jonathan Choi, Alex Huh

Installation:
- Clone or download from the repository
- Use npm install to install the needed node modules

Singleplayer features include:
- Settings
  - ARR
    - ARR is auto repeat rate (how quickly the pieces move from right to left.)
  - DAS
    - DAS is delayed auto shift (How long you have to hold down the button to before a piece starts flying to the wall)
  - 180 degree rotations
  - Simple keybind changes
- Statistics
  - Time
  - Pieces Placed
  - Finesse score
  - Spins
  - Lines Cleared
- Game Modes
  - Free play
    - Allows the user to play however long they want with no restrictions on finesse
  - Sprint
    - Times how fast the user can clear 40 lines. Timer stops when the user clears at least 40 lines
  - Finesse Trainer
    - Any tetris piece can be put on any spot of the board in 3 moves of less. Finesse Trainer is used for efficiecy training. It includes the show feature and the redo feature in the settings, which allows the user to either see the finesse error without having to redo it, or makes the user redo every finesse error.

Multiplayer features include:
- 1v1 another user through the website
- Garbage is sent to the other user based on lines cleared
- The user that reaches the top of the board loses
- Requires a server to run
- Uses websockets from ws.io and express.io to communicate between clients and the server
- Has garbage lines and opponent actions displayed
