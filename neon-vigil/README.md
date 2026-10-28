# NV Mesh Viewer

This is the NV Mesh Viewer demo in the model-viewer fork. It is a new, separate demo in `neon-vigil/` and is separate from the game repo. It does not modify the model-viewer library source code.

Open `neon-vigil/index.html` to view the demo. It loads model-viewer from CDN and uses the Neon Vigil palette. The page is a scrollable gallery: one section per model, stacked vertically, each with its model name as a heading and a model-viewer with camera-controls and auto-rotate.

## Models

The gallery loads, in order, from `neon-vigil/models/`:

- `infinity6-spaceship-package.glb` (first, at the top)
- `infinity6-animated-ramp-airlock.glb`
- `infinity6-shapewarp.glb`
- `infinity6-verans.glb`
- `infinity6-lockfit-solid.glb`
- `infinity6-detailed.glb`
- `infinity6-clunky.glb`
- `infinity6-window-proof.glb`
- `infinity6-recolored.glb`
- `infinity6-lockfit.glb`

## How to add a GLB

1. Add your GLB file to `neon-vigil/models/`.
2. Open `neon-vigil/index.html` and add a section with a heading and a model-viewer whose `src` points to the GLB you added.

## Neon Vigil palette

- Dark: #0a0a12
- Pink: #ff2da6
- Cyan: #00e5ff
- Text: white
