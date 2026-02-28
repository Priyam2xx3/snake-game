# Retro Nokia Snake Game 🐍

A classic, fully playable Snake game built with HTML5 Canvas, CSS, and Vanilla JavaScript. It features a nostalgic "Retro Nokia" aesthetic, complete with the iconic green screen and pixelated graphics!

## Features

- **Classic Gameplay**: Move in four directions, eat food to grow, and try to get the highest score. Watch out for the walls and your own tail!
- **Retro Aesthetic**: Designed to look like a classic Nokia phone screen with a `#879477` background, dark UI surrounding the container, and a pixelated snake.
- **Responsive Controls**:
  - Play with the **Arrow Keys** (Up, Down, Left, Right).
  - Play with **W, A, S, D**.
  - Includes an **on-screen D-Pad** that appears automatically on mobile devices or smaller screens for touch control.
- **Score Tracking & Persistence**: Tracks your current score. Your High Score is saved in the browser's `localStorage`, so your best run won't be lost when you refresh the page.
- **Dynamic Speed Scaling**: The game gets harder the longer you play! The snake's speed increases by 5% every time you eat 5 pieces of food.
- **Power-Ups (Golden Apple)**: Keep an eye out for the Golden Apple! It occasionally spawns, gives double points, but blinks and disappears after 5 seconds if you don't catch it.
- **Single File Structure**: The entire game (HTML structure, CSS styling, and JS logic) is contained within a single `index.html` file for ultimate portability.

## How to Play

1. **Clone or Download**: Download the `index.html` file to your computer.
2. **Open in Browser**: Double-click the `index.html` file to open it in any modern web browser.
3. **Start Moving**: Use the arrow keys, WASD, or the on-screen D-pad to start moving the snake. The game begins immediately!

## Customization

Since the code is all in one place, it's very easy to tweak! Open `index.html` in your favorite text editor to play around with these settings:
- **`baseDelay`**: Change the initial speed of the game (lower is faster).
- **`scale`**: Change the size of the snake and the grid cells.
- **Colors**: Look in the CSS `<style>` block to modify the Nokia green (`#879477`) or black (`#111`) to any color scheme you want!

Enjoy!
