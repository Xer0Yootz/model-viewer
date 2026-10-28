# Neon Vigil — Model Viewer

This is the Neon Vigil-themed viewer demo in the model-viewer fork. It is a new, separate demo in `neon-vigil/` and is separate from the game repo. It does not modify the model-viewer library source code.

Open `neon-vigil/index.html` to view the demo. It loads model-viewer from CDN and uses the Neon Vigil palette.

## How to add a GLB

1. Add your GLB file to `neon-vigil/models/`.
2. For the examples in the demo, use `neon-vigil/models/val17.glb` for Val 17 and `neon-vigil/models/infinity6.glb` for the Infinity 6.
3. Open `neon-vigil/index.html` and use the "Val 17" or "Infinity 6" buttons to load the matching model, or set the model-viewer `src` to the GLB you added.
4. Until a real model is added, the demo uses `neon-vigil/models/placeholder.glb` as its placeholder `src`.

## Neon Vigil palette

- Dark: #0a0a12
- Pink: #ff2da6
- Cyan: #00e5ff
- Text: white
