# galaxy-simulation
An interactive pink galaxy simulation built with HTML5 Canvas and vanilla JavaScript.

The project creates a dynamic pink galaxy made of more than a thousand animated stars orbiting around a central gravitational point. Users can also interact with the simulation by creating additional gravity points directly on the canvas.

## Features

- Interactive galaxy simulation
- 1,100 animated stars
- Custom gravitational physics
- Click or tap to create gravity points
- Up to three additional attractors at the same time
- Pause and resume the animation
- Remove gravity points
- Restart the simulation
- Responsive canvas
- High-DPI display support
- Reduced-motion accessibility support
- Pink galaxy-inspired visual design

## Built With

- HTML5
- CSS3
- JavaScript
- HTML Canvas API

No frameworks or external libraries are required.

## How It Works

Each star has its own position, velocity, size, and color.

The simulation applies gravitational acceleration toward the center of the galaxy and toward any additional gravity points created by the user.

The stars are continuously updated using JavaScript and rendered through the Canvas API using `requestAnimationFrame()`.

A fading background effect is also used to create subtle motion trails as the stars move.

## Controls

**Pause**  
Stops the galaxy animation.

**Resume**  
Continues the animation.

**Remove Attractors**  
Removes all custom gravity points.

**Restart**  
Generates a new galaxy and resets the simulation.

**Click / Tap on the Galaxy**  
Creates an additional gravity point at that position.

## Project Structure

```text
pink-galaxy-simulation/
│
├── index.html
├── README.md
└── LICENSE
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/pink-galaxy-simulation.git
```

Open the project folder:

```bash
cd pink-galaxy-simulation
```

Then open `index.html` in your browser.

No installation or build process is required.

## Possible Improvements

Some ideas for future versions:

- Adjustable gravity strength
- Star density controls
- Multiple galaxy shapes
- Different color themes
- Zoom and camera controls
- Black hole effects
- Mouse-controlled gravity
- Performance settings for different devices

## Author

Created by **Vannesa Pulido**

## License

This project is licensed under the MIT License.
