# Star Trail Animation

## Overview

This project creates a visually appealing star trail animation using JavaScript, HTML, and CSS. The animation activates on mouse movement, creating sparkling stars and a glowing trail as the cursor moves across the screen.

## Files in this Repository

- `index.html`: The HTML file for the project, which sets up the structure for the star trail animation.
- `style.css`: Contains the styling required for the star trail animation, including star sizes, colors, and animations.
- `script.js`: JavaScript code that handles the creation and animation of stars and glow points as the mouse moves.

## Features

- **Star Creation**: Stars are generated where the mouse cursor moves.
- **Glow Effect**: A glowing trail follows the mouse cursor, enhancing the visual effect.
- **Customizable Parameters**: The script allows customization of various parameters including star size, color, and animation duration.

## Configuration

The `config` object in the JavaScript file allows you to customize:
- Star animation duration
- Minimum time and distance between star creation
- Glow effect duration and spacing
- Star colors and sizes
- Different star fall animations

## Utility Functions

A set of utility functions are provided for random selection, unit conversion, distance calculation, and time calculation.

## Star and Glow Point Creation

- `createStar`: Function to create a star element at a specified position.
- `createGlowPoint`: Generates a glow point.
- `createGlow`: Creates multiple glow points between two positions to form a continuous glowing trail.

## Event Handling

- `handleOnMove`: Main event handler for mouse or touch movement, responsible for creating stars and glow effects.
- `window.onmousemove` and `window.ontouchmove`: Event listeners for mouse and touch movements.

## License
This project is open source and available under the [MIT License](LICENSE).
