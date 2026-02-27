# Test Module (OMF 0.1)

Scaffolded OMF module for testing. Replace placeholder `content_hash` and `canonical_id` after adding content and running your canonical hashing implementation.

## Structure

- `module.json` — module metadata (required)
- `content/` — main module content (required)
- `license.txt` — license text (required)
- `assets/` — optional media/assets (included in canonical hash)
- `assets/link-previews.json` — optional build-time link preview metadata (URL → title, description, image); if present, included in hash
- `assessments/` — optional assessments

## Next steps

1. Add content under `content/`.
2. Add any external resource URLs to `external_resources` in `module.json`.
3. Compute SHA-256 canonical hash (module.json minus content_hash/canonical_id, content/, assets/, license.txt, external resource metadata).
4. Set `content_hash` and `canonical_id` in `module.json`.
