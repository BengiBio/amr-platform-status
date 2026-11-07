# AMR platform status (live, display only)

Live page: https://bengibio.github.io/amr-platform-status/

- `index.html` (branch `main`) is the page. It polls the single-commit branch `feed` (`status.json`) every 30 s.
- `status.json` is published by the platform's `public_feed.py`: the platform's status snapshot with server paths and
  file names removed. The `feed` branch is force-pushed on each update and keeps one commit.
