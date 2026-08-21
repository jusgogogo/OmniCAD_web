# OmniCAD interactive 3D assets

The supplied OmniCAD paper and supplementary package do not contain GLB/GLTF/OBJ sample models, so this folder is intentionally left without model binaries.

The webpage already includes the same Three.js + GLTFLoader + OrbitControls interaction pattern used by the reference OmniLayout/OmniMech site. Add GLB files using these names and reload the page:

- `case-01-gt.glb` — ground truth
- `case-01-gpt55.glb` — GPT-5.5 prediction
- `case-01-gemini31.glb` — Gemini 3.1 Pro prediction
- `case-01-claude48.glb` — Claude Opus 4.8 prediction
- `case-01-qwen37.glb` — Qwen3.7-Plus prediction

No JavaScript changes are required for these five slots. The viewer supports drag-to-orbit, wheel/pinch zoom, automatic centering/scaling, shared WebGL rendering, and light/dark theme material adaptation.

For additional cases, duplicate the model cards in `index.html` and point `data-src` to the desired `.glb` path.
