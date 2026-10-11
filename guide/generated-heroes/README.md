# Guide landing-page hero photography

Seven illustrative photos generated on 11 October 2026 with the built-in image generation tool. These are generated scenes, not documentary photographs of named landmarks or Winter Scape activities.

The exact prompts, target filenames and owning seed files are recorded in `prompts.json`. The selected images are stored in `../photos/` with the `2026-10-guide-` prefix. Each is 1672 × 941 pixels and encoded as WebP at quality 90; no scene edits, baked overlays or crops were applied.

Each main-page YAML references its image through `hero_image: media/photos/...` and provides descriptive alternative text under `media.alt`. The existing guide media importer sets the page featured image. The theme supplies the navy hero overlay and responsive crop.

After changing an image, run `scripts/update-seed-media-manifest.py` from the website repository to refresh the shared checksums. Commit and push this media repository before deploying a website revision that references these assets.
