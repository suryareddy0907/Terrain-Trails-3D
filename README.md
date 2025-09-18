`Terrain Trails 3D` is a **procedural terrain generation engine** for use with the
[Three.js](https://github.com/mrdoob/three.js) 3D graphics library for the web.

## Usage

You can download the script normally, install it with Bower (`bower install
THREE.Terrain`), or install it with npm (`npm install three.terrain.js`). To
include it on a page client-side without a module loader:

```html
<!-- from a direct download or git clone -->
<script src="build/THREE.Terrain.min.js"></script>

<!-- from Bower -->
<script src="bower_components/THREE.Terrain/build/THREE.Terrain.min.js"></script>

<!-- from npm -->
<script src="node_modules/three.terrain.js/build/THREE.Terrain.min.js"></script>
```

You then have access to the `THREE.Terrain` object. (Make sure the `three.js`
library is loaded first.)

### Procedurally Generate a Terrain

Methods for generating terrain procedurally that are available
include Cosine, Diamond-Square (a better version of Midpoint Displacement),
Fault lines, Feature picking, Particle deposition, Perlin and Simplex noise,
Value noise, Weierstrass functions, Worley noise (aka Cell or Voronoi noise),
Brownian motion, arbitrary curves, and various combinations of those.

## Screenshots

![Screenshot 1](https://raw.githubusercontent.com/IceCreamYou/THREE.Terrain/gh-pages/demo/img/screenshot1.jpg)
![Screenshot 2](https://raw.githubusercontent.com/IceCreamYou/THREE.Terrain/gh-pages/demo/img/screenshot2.jpg)
