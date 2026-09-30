# 3D Animal Website

A tiny interactive 3D animal sanctuary built with [Three.js](https://threejs.org/).

Four animated low-poly animals — a fox, a wolf, a stag, and a horse — roam a
floating island meadow. Click an animal to follow it, pause the wandering, or
switch between day and dusk lighting.

## Run locally

```bash
# from this directory
python3 -m http.server 8080
# then open http://localhost:8080/
```

No build step needed — it's a single static page. Three.js loads from a CDN;
the animal models live in `models/`.

## Credits

Animal models by [Quaternius](https://quaternius.com/) — public domain (CC0),
from the *Ultimate Animated Animals* pack.
