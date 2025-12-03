# 2D_3D_learn

This project is a collection of interactive examples to learn about 2D and 3D graphics on the web, using different rendering technologies.

## Project Structure

The project contains HTML files that demonstrate animations of circles (2D) and spheres (3D) using three main approaches:

### 2D
- **2D_CPU.html**: Rendering of an animated circle using pure JavaScript and the Canvas 2D context (CPU processing).
- **2D_CSS.html**: Animation of a circle using CSS properties and transitions.
- **2D_GPU.html**: Rendering of a circle using Three.js (GPU acceleration with WebGL).

### 3D
- **3D_CPU.html**: 3D simulation of a sphere using JavaScript and Canvas 2D (CPU processing, no real WebGL).
- **3D_CSS.html**: 3D animation using CSS transforms and perspectives.
- **3D_GPU.html**: Full 3D rendering using Three.js with WebGL.

## Common Features
- Interactivity: Objects respond to mouse (hover, drag).
- Adjustable configurations: Initial position, colors, speeds, maximum FPS.
- FPS counters to measure performance.
- Smooth return animations when the object is released.

## How to Use
Open any of the HTML files in a modern web browser. The examples are self-contained and do not require a local server.

## Technologies
- HTML5 Canvas
- CSS3 Animations/Transforms
- JavaScript (ES6+)
- Three.js (for GPU versions)
