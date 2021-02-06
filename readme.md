This repository contains a simple coursework project that was written for a visual computing unit at university.

Project can be previewed [here](https://damianhaziak.github.io/WebGLObjectSandbox/dh651%20-%20WebGL%20Coursework.html "WebGL Object Sandbox").

It explores the Web Graphics Library (WebGL) API through the `three.js` library. A cube is rendered and textured using the latter. Camera movements and object rotations are implemented, and you can manipulate them using the controls below:

Rotation controls:
* `x` : enable x axis rotation for the cube/object
* `y` : enable y axis rotation for the cube/object
* `z` : enable z axis rotation for the cube/object

Camera orbit controls (defined as an orbit rotation around the camera view center, which is initialized as the axis origin however it can be translated using the camera translation controls):
* `u` : orbit camera up
* `j` : orbit camera down
* `h` : orbit camera left
* `k` : orbit camera right

Camera translation controls:
* `up arrow` : translate camera center up
* `down arrow` : translate camera center down
* `left arrow` : translate camera center left
* `right arrow` : translate camera center right
* `numpad +` : translate camera center forward
* `numpad -` : translate camera center backward

Other controls:
* `b` : toggle between the Rubic's cube (default) and a bunny mesh render
* `v` : vertex rendering mode, renders each vertex of the current object as a point
* `e` : edge rendering mode, renders edges of the current object 
* `f` : face rendering mode, renders faces of the current object (default)
* `s` : "super" mode toggle, rotations speed up and the ambient light is replaced with a point light of a random colour (also included some music, however that is removed as it was annoying)

[*WebGL Report.pdf*](../master/WebGL%20Report.pdf) goes into more detail regarding the implementation of this, so please refer to that document for more information.

## Dependencies

* [`three.js`](https://threejs.org/) (included)
* `OBJLoader.js` (included)
* A server, any will do, I used Python's `http.server`
