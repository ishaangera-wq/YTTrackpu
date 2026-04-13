# YTTrackpu

Public static frontend for the YouTube livestream tracker.

This repository is meant to host:

- `index.html`
- `cnbc_tv18_streams.json`
- `cnbc_tv18_streams.csv`

The files are refreshed by the private source repository workflow.

## Important

Do not expose a GitHub token in browser-side JavaScript.

If the public frontend needs data from the private repo, use a GitHub Actions secret in the private repo and publish the generated static files into this repository.
