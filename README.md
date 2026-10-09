# Simon Says Game

A browser-based Simon Says memory game built with vanilla HTML, CSS, and JavaScript. Watch the sequence of flashing colors, then repeat it in the same order. Each level adds one more color.

## How to Play
1. Open the game and press **any key** on your keyboard to start.
2. Watch the sequence of colors that flash (the game adds one new color every level).
3. Repeat the sequence by clicking the colored buttons in the same order.
4. If you repeat it correctly, you move to the next level.
5. One wrong click ends the game, the screen flashes red, and your final score (the level you reached) is shown.
6. Press any key to play again.

## Features
- Random color sequence that grows by one each level
- Separate flash effects for the game (white) and for your clicks (faded white)
- Live level display
- Game Over message with your score and a red screen flash
- Instant restart by pressing any key
- Runs in any modern browser, with no installation or libraries needed

## Technologies Used
- HTML5
- CSS3 (Flexbox)
- JavaScript (vanilla)

## Project Structure
```
Simon-saya-Game/
├── index.html    # Game layout (4 colored buttons)
├── style3.css    # Styling and flash effects
└── app2.js       # Game logic (sequence, user input, level, game over)
```

## How to Run
1. Clone the repository:
```bash
   git clone https://github.com/priyankapanigrahi398-sys/Simon-saya-Game.git
```
2. Open the project folder.
3. Double-click `index.html` to open it in your browser.

## How It Works
- `levelUp()` increases the level and flashes a new random color, storing it in the game sequence.
- `btnPress()` records the color the player clicks.
- `checkAns()` compares the player's sequence with the game's sequence. A full match starts the next level, and a mismatch ends the game.
- `reset()` clears everything so a new game can start.

## Future Improvements
- Sound effects for each color
- High score saved with localStorage
- Mobile-friendly touch controls and a Start button
- Increasing speed at higher levels

## Author
Priyanka Panigrahi
