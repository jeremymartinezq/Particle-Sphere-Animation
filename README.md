# Particle Sphere and Orbits

A 3D visualization of a colored particle sphere with orbiting rings, created using HTML, CSS, and JavaScript with Three.js.

![Screenshot 2025-05-04 164130](https://github.com/user-attachments/assets/5773e46b-59a0-4a5c-abaf-1b14dc3b23d5)


## Live Demo

Open `index.html` in your browser to view the interactive demo.

## Features

- Interactive 3D particle sphere with gradient coloring
- Animated orbital rings with vibrant neon colors
- Dynamic camera controls for exploring the visualization
- Responsive design that adapts to window size
- Pure JavaScript implementation with Three.js

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Three.js](https://threejs.org/) - JavaScript 3D library

## How It Works

The visualization consists of several key components:

1. **Central Sphere**: A solid colored sphere with a semi-transparent surface
2. **Particle Layer**: 30,000 individual particles distributed on the sphere's surface with color gradients
3. **Orbital Rings**: Three distinct orbital rings with different colors, sizes, and rotation patterns
4. **Ambient Particles**: Random particles scattered throughout the scene for added depth

The colors transition from purple at the bottom to blue in the middle and cyan at the top, creating a vibrant visual effect.

## Controls

- **Rotate**: Click and drag to rotate the view
- **Zoom**: Use the mouse wheel to zoom in and out
- **Pan**: Right-click and drag (or use middle mouse button) to pan the view

## Customization

You can easily customize various aspects of the visualization by modifying parameters in the code:

- Change colors by adjusting the RGB values
- Modify particle counts for performance optimization
- Adjust orbit sizes and rotation speeds
- Change the sphere size and opacity

## Performance Notes

The visualization uses thousands of particles which may affect performance on lower-end devices. If you experience lag, consider reducing the particle count in the following variables:

- `particleCount` (currently 30,000)
- Orbit particle counts (currently 2000-3000 per orbit)
- `ambientCount` (currently 2000)

## License

[MIT License](LICENSE)

## Acknowledgments

- Inspired by cosmic and particle visualizations
- Built with [Three.js](https://threejs.org/)

## Author 
Developed by Jeremy Martine-Quinones.
