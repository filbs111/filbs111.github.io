## Overview of (some of) [filbs111's github projects](https://github.com/filbs111)

### 1) Wide angle camera (webgl)

[![Preview](https://imgoat.com/uploads/82be0c5cdc/32458.png)](http://filbs111.github.io/webgl-wideanglecamera)

Webgl implementation of fisheye / stereographic projection camera, so can show greater than 180 degrees field of view than possible with standard rectilinear projection camera, or smaller angles with less perceived distortion. Useful for games because player can be aware of surroundings without control input to look around. [Demo](http://filbs111.github.io/webgl-wideanglecamera) &#124; [Code](http://github.com/filbs111/webgl-wideanglecamera)

### 2) Hyperspace explorer (webgl)

[![Preview](https://imgoat.com/uploads/82be0c5cdc/32460.png)](http://filbs111.github.io/3sphere-explorer)

Universe is the surface of a 3-sphere, which is to 4D space what a globe is to 3D space. The player can fly straight in any direction, and return to their starting point. [Demo](http://filbs111.github.io/3sphere-explorer) &#124; [Code](http://github.com/filbs111/3sphere-explorer)

### 3) Spherical portals / reflectors (webgl)

[![Preview](https://imgoat.com/uploads/82be0c5cdc/32459.png)](http://filbs111.github.io/webgl-reflections)

Drawing mirror sphere in webgl, which can be used as a portal (similar to how planar portals are similar to regular mirrors). Intended to be used with project 2) to link 3-sphere worlds. [Demo](http://filbs111.github.io/webgl-reflections) &#124; [Code](http://github.com/filbs111/webgl-reflections)

### 4) Precalculated lighting for arbitrary gradient skylight

Lighting by a skylight with colour gradient, in realtime, using a pregenerated texture, containing the result of lighting by an isotropic skylight, and 3 skylights with gradient aligned with the cartesian axes. AFAIK equivalent to "spherical harmonic" lighting, for the first 4 harmonics. [Demo](http://filbs111.github.io/shadertest) &#124; [Code](http://github.com/filbs111/shadertest)

### 5) Rotate and thrust shooter 1

Older effort at Gravity Force 2 clone using html5 canvas, storing levels like bitmaps. [Demo](http://filbs111.github.io/turn-n-burn/game.html) &#124; [Code](http://github.com/filbs111/turn-n-burn)

### 6) rotate and thrust shooter 2

Uses box2d and clipper libraries (vector levels).  [Demo](http://filbs111.github.io/box2d-learning) &#124; [Code](http://github.com/filbs111/box2d-learning)
