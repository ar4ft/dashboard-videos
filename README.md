# dashboard-videos

Video News MP4s (720×1280, H.264/AAC) for [ar4ft/personal-dashboard](https://github.com/ar4ft/personal-dashboard),
served through jsDelivr with URLs pinned to commit SHAs:
`https://cdn.jsdelivr.net/gh/ar4ft/dashboard-videos@<sha>/<slug>.mp4`.

Managed by `video/make.py --host jsdelivr` in the dashboard repo. Do not edit by hand.

- `main` holds only this README.
- Videos live on orphan branches `v-YYYYMMDD-N`, each kept under ~40 MB (jsDelivr's whole-ref fallback limit is 50 MB).
- Retention: a `v-*` branch is deleted once every video on it is older than 60 days and not pinned.
- Pinned (keep forever) videos are copied to `pinned-N` branches before their day branch is deleted.
- Narration scripts and captions are in the dashboard repo; everything here is generated media.
