# Vite Project 1

Welcome to **Vite Project 1**! This project is a modern web application demonstrating the usage of **WebGL**, **Canvas**, and **Three.js** for rendering 3D graphics on the web. Built using **Vite**, this app showcases how to integrate 3D graphics into web applications with ease.

## Live Demo

You can view the live version of this project here:

[Live Demo](https://anis196.github.io/vite-proj-1/)

## Features

- 3D graphics rendered using **Three.js**
- Interactive scenes with camera controls
- Real-time rendering with **WebGL** and the **Canvas** API
- Lightweight build configuration with **Vite**
- Performance optimization for web-based 3D graphics

## Concepts Explained

### WebGL

[WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) (Web Graphics Library) is a JavaScript API that enables rendering 3D graphics inside a web browser without the need for plugins. It provides an interface to OpenGL ES (a subset of OpenGL), and it's supported in most modern browsers. 

Key points about WebGL:
- **Hardware-accelerated** graphics rendering.
- **Low-level API**: WebGL exposes a low-level, shader-based API to interact directly with the GPU.
- WebGL allows **interactive 3D content** on web pages, such as games, simulations, and data visualizations.

### Canvas API

The [HTML5 Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) is a drawing surface provided by the `<canvas>` element in HTML. It allows for dynamic, scriptable rendering of 2D shapes and bitmap images, and it can be used for both 2D and 3D graphics (using WebGL).

Key points about Canvas API:
- The `<canvas>` element is where we render content using JavaScript.
- For 2D graphics, you use the `getContext('2d')` method.
- For 3D graphics, you use WebGL, which operates directly on the `<canvas>` element for GPU-accelerated rendering.

### Three.js

[Three.js](https://threejs.org/) is a JavaScript library that simplifies the creation and manipulation of 3D content for the web. It abstracts much of the complexity of using WebGL directly, making it easier to render 3D scenes and objects in the browser.

Key points about Three.js:
- **Scene Graph**: Three.js uses a scene graph where objects are added to a scene, and then rendered with a camera.
- **Camera**: The camera defines the view of the scene. There are different types of cameras like `PerspectiveCamera` and `OrthographicCamera`.
- **Lighting**: Various types of light sources are available, such as directional lights, ambient lights, and point lights, which affect how objects are lit in the 3D space.
- **Materials & Textures**: Three.js provides a variety of materials (such as MeshBasicMaterial, MeshStandardMaterial, etc.) that determine how objects appear in terms of color, reflectivity, and texture.
- **Geometry**: Three.js has pre-built geometries like cubes, spheres, and planes, but you can also create custom geometries.

## Project Setup

### Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/anis196/vite-proj-1.git
