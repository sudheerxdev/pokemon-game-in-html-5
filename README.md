# Pokemon Game in HTML5

A browser-based Pokemon-themed arcade game built with plain HTML5, CSS, JavaScript, and Canvas.

## Overview

This project contains a 3-level game where the player controls Pikachu, avoids enemies, and reaches the goal before time runs out. The game includes animated start, victory, and game-over screens with audio and image assets.

## Gameplay

- Start from `Pokemon Game/1.Start The Game.html`
- Progress through three levels:
  - `2.advancedPokemonGame_1.html` (grass theme)
  - `3.advancedPokemonGame_2.html` (water theme)
  - `4.advancedPokemonGame_3.html` (fire theme)
- Reach the goal Pokeball on each level to continue
- Avoid enemy collisions and beat the timer
- Lives and score are persisted in `localStorage`
- End screens:
  - `5.gameEnd.html` for victory
  - `6.gameOver.html` when all lives are lost

## Controls

- Hold mouse click (desktop) or touch (mobile) to move Pikachu forward
- Release to stop movement

## Run Locally

### Option 1: Open directly

1. Open `Pokemon Game/1.Start The Game.html` in a modern browser.

### Option 2: Use a local server (recommended)

If assets/audio fail to load due to browser security rules, serve the folder locally:

```bash
# Python 3
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/Pokemon%20Game/1.Start%20The%20Game.html
```

## Project Structure

```text
Pokemon Game/
  1.Start The Game.html
  2.advancedPokemonGame_1.html
  3.advancedPokemonGame_2.html
  4.advancedPokemonGame_3.html
  5.gameEnd.html
  6.gameOver.html
  assets/
  audio/
  fire/
  grass/
  water/
  pokeSong/
```

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas API
- Browser `localStorage`

## Notes

- This project is asset-heavy (images/audio), so first load may take longer.
- Audio autoplay can be blocked by browsers until first user interaction.
