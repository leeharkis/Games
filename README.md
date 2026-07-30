# OtherGames - Games Package

## Games Included

1. **Battlezone** - Classic vector tank game
2. **BattlezoneSolid** - Solid version of Battlezone
3. **Chess** - Full chess game with capture panel
4. **Chess Silly** - Chess variant with captures below board
5. **Daredevil Denis** - Platform runner with mobile controls
6. **Space Invaders** - Classic Space Invaders
7. **Sudoku** - Sudoku puzzle solver with highlighting
8. **Sudoku Mobile** - Mobile optimized Sudoku
9. **Tetris** - Classic Tetris game
10. **Tetris Mobile** - Mobile optimized Tetris
11. **Dots** - Connect-the-dots puzzle game
12. **Elite Space Combat** - 3D space dogfighting with trading

## Quick Start

1. Extract the OtherGames-Package.zip file
2. Open `index.html` in a web browser
3. All games are playable immediately - no installation needed

## Controls

### General
- Click on any game to play
- Each game has its own control scheme (shown in-game)

### Elite Space Combat
- **Arrow Keys** - Pitch/Roll
- **W/S** - Speed up/down
- **Space** - Fire weapons
- **L** - Land on planets
- Approach within 80m of a planet to dock

### Sudoku
- Click cells to select
- Click number buttons to place/remove
- Double-click grid number to select that number
- Check button validates solution

### Dots
- Drag to connect 2+ circles of same color
- Connected circles disappear, others fall down
- Enclosed circles also disappear
- Choose 60-second or 25-move challenge

### Chess Games
- Click piece then click destination
- Captures shown below board
- Undo button available

### Daredevil Denis
- Mobile: Touch buttons at bottom
- Desktop: D/Right = Accelerate, A/Left = Brake, Space = Jump

### Tetris
- Arrow keys to move
- Space/Up to rotate
- Try to clear lines

## Continuing on Mac

1. Extract the zip file on your Mac
2. Open `index.html` in any browser
3. The games are completely self-contained - no server needed
4. All high scores and game data are saved in browser localStorage
5. To continue developing:
   - Edit HTML files directly in any text editor
   - Save files and refresh browser to see changes
   - Use browser Developer Tools (F12) to debug

## Features

- **Offline Play** - Service worker caches all files for offline play (after first visit)
- **Local Storage** - High scores saved in browser
- **Responsive Design** - Works on desktop, tablet, and mobile
- **No Dependencies** - Pure HTML/CSS/JavaScript
- **Easy Docking** - Elite game docking simplified vs original

## Development Notes

- All games use vanilla JavaScript (no frameworks)
- Canvas-based rendering for graphics
- localStorage API for persistence
- Service worker for offline functionality

## To Continue Development

Simply edit the HTML files and refresh the browser. Each game is self-contained in a single HTML file for easy portability.

---
Created: July 28, 2026
