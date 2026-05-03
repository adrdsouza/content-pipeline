# Puck — Ingredient References

Persistent reference images for the Damned Designs Puck ad pipeline. These are passed as Ingredients-to-Video / multi-image refs to NB2 + Veo 3.1 / Kling 3.0 Pro / Seedance 2.0 to lock product identity across shots.

| File | Purpose |
|---|---|
| [`puck_ref.png`](puck_ref.png) | Studio shot of the Puck — locks product geometry, finish, LED row across every generated frame |
| [`iphone_ref.png`](iphone_ref.png) | Bare orange titanium iPhone Pro back — locks phone geometry/color across every shot |
| [`env_ref.png`](env_ref.png) | Brutalist concrete corridor with FLW windows — locks environment for shot 4 (walk-away) |

## Stable URLs

```
https://raw.githubusercontent.com/adrdsouza/content-pipeline/master/puck/puck_ref.png
https://raw.githubusercontent.com/adrdsouza/content-pipeline/master/puck/iphone_ref.png
https://raw.githubusercontent.com/adrdsouza/content-pipeline/master/puck/env_ref.png
```

These bypass fal/WaveSpeed temp storage (which has 1h TTL) — the pipeline's `ensureRemoteUrl` helper passes `raw.githubusercontent.com` URLs through unchanged.

## Source

Generated 2026-05-03 via NanoBananaAPI 2K resolution. Prompts in `D:\Claude\Roadmap\Launches\puck\images\ad-v2\01-storyboard.mjs`.
