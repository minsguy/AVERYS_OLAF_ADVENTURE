# AVERY'S OLAF ADVENTURE

A simple HTML5 browser game made for a 4-year-old. Olaf catches snowflakes and Princess Avery while avoiding fire and sun.

## How to Play
- Open `index.html` in any browser (double-click)
- Move Olaf left/right with arrow keys (or WASD), or tap left/right side on touch devices
- Catch snowflakes and Princess Avery (good items) - they float down slowly with sparkles
- Avoid fire and sun (bad items) - they fall fast with scary glow
- Start with 3 snowballs, win at 10, lose at 0

## Tech Stack
- Single `index.html` file (~1000 lines) containing all HTML, CSS, and JavaScript
- No dependencies or build process
- Web Audio API for sound effects (no audio files needed)
- SVG graphics for snowflake, fire, and sun (embedded inline)

## Key Files
- `index.html` - The entire game
- `olaf.png` - Main character sprite
- `princess_avery.png` - Princess sprite (falling item + win screen)

## Game Features
- **Good items**: Snowflake (SVG), Princess Avery (150px PNG) - float slowly with sparkle glow
- **Bad items**: Fire, Sun (SVG with angry face) - fall fast with red/orange pulse
- **Effects**: Screen shake on hit, sparkle explosion on catch, Olaf hurt animation
- **Heat system**: Background gradient shifts blue→red as snowballs decrease
- **Win screen**: Olaf and Avery side by side as best friends
- **Lose screen**: Olaf melts into a puddle

## Design Decisions
- Very Easy difficulty: 70% good items, slower speeds (4-year-old friendly)
- Generous hitboxes for catching, smaller hitboxes for avoiding
- Princess Avery falls at 150px size for visibility
- Win screen: Olaf 280px with margin-bottom to align with Avery's height
- Sound effects are synthesized (magical chime for good, wobbly tone for bad)

## Intro Copy (Olaf's voice)
- "I LOVE snowflakes and Princess Avery! ❄️"
- "Can you help me catch them?"
- "Uh oh... fire and the sun make me melt!"
