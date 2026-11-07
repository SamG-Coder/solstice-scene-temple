# Solstice scene: temple

The temple scene for [Solstice](https://github.com/SamG-Coder/solstice): a ruined temple in a desert canyon, entirely procedural.

GitHub Pages serves it at `https://samg-coder.github.io/solstice-scene-temple/web.solstice`, where the
[viewer](https://samg-coder.github.io/solstice/) streams it with range requests. It is served
from its own site, on the same domain as the viewer, so that publishing it never redeploys the
viewer or the other scenes, and browsers can read it, which they cannot from a release.

`scene.txt` names the release holding the scene and its SHA-256. Scenes are baked on a PC and
published with `scripts/publish-scenes.py` in the main repository, which uploads a new release
here and updates `scene.txt` only when the scene's content changes.
