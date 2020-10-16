# MGL-starter
MakeGL Startup Repro - Web 3D and VR. 

## About MakeGL
MakeGL is a javascript library for making rich and immersive 3D content on the web. It is small, fast and works.

## Using
Embedding a 3D scene onto a page requires ...
1. Add a target canvas
```
<canvas id="makeGLCanvas"></canvas>
```

2. Include the library
```
<script src="./MGL/mgl.js"></script>
```

3. Hook-up the desired scene to the canvas
```
<script>var mGL = new MGL.Scene('makeGLCanvas', "./scene.json");</script>
```

## Defining the scene
As you may have already noticed scenes are defined in simple JSON files that are easy to read and edit. (coming soon is a visual editor).
