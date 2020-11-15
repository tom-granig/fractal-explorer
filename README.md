# fractal-explorer
Zoom in and around a fractal right in your browser with GPU acceleration. The fractal is computed by the GPU in the fragment shader using the WebGL API. You can save locations that you visit to jump to later. Write your own GLSL code with the built-in code editor to generate different fractals. The default code generates the Mandelbrot Set, going to 100 iterations.

![Mandelbrot Set - Frctal Explorer](https://tom-granig.github.io/fractal-explorer/screenshots/fractal1.png)

## Controls
#### Desktop
* Hold down the left mouse button and drag to pan
* Toggle panning by clicking the right mouse button
* You can also pan using the arrow keys or W, A, S and D
* Use the scroll wheel or Z and X to zoom in and out

#### Mobile
* Drag your finger in the direction you want to pan
* Pinch to zoom in and out

#### Inputting coordinates and zoom factor
Type in the coordinates you want to jump to

## Code Editor
The code editor allows you to edit the fragment shader GLSL code which is run. It has syntax highlighting and basic auto-formatting. Compile errors are shown by highlighting the relevant line as well as providing the error at the top of the display.
