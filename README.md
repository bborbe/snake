# Snake

Classic Snake game implemented in vanilla JavaScript.

**Play online:** https://bborbe.github.io/snake/

## Features

- Smooth snake movement
- Progressive speed increase
- Speed boost with spacebar
- High score tracking
- Pause functionality
- Collision detection

## How to Play

Open `index.html` in browser.

### Controls

- `←` `→` `↑` `↓` - Change direction
- `Space` - Speed boost
- `P`/`Esc` - Pause
- `R` - Restart

## Gameplay

- Eat red food to grow and score points
- Game speeds up every 50 points
- Avoid hitting walls or yourself
- Use speed boost for precise movements

### Scoring

- Each food: 10 points
- Speed level: score ÷ 50 + 1

## Technical

- Pure JavaScript (no dependencies)
- LocalStorage for high score persistence
- Modular architecture (GameState, Renderer, InputHandler)
- 30×30 grid, 20px cells
- Dynamic speed scaling
