# Winter Scape seed media

Owner-authorized website photographs used by the Winter Scape WordPress content seeder. This repository is a seed source, not the visitor-facing media host.

## Structure

- `volunteer/`: volunteer program photographs
- `guide/photos/`: Sri Lanka guide photographs
- `tours/photos/`: tour and category photographs

Edit files here, regenerate the website plugin manifest with `python3 scripts/update-seed-media-manifest.py`, commit and push this repository, then update and commit the website submodule reference and manifest. Imports use local files first, otherwise GitHub raw URLs. Existing WordPress attachments are retained; replacing already imported media is a separate deliberate action.

These photographs are not licensed for unrelated reuse.
