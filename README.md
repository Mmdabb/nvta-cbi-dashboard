# NVTA Corridor Performance Dashboard

This public repository contains the static, published NVTA CBI integrated
corridor dashboard.

**Live dashboard:** <https://mmdabb.github.io/nvta-cbi-dashboard/>

The current publication contains 225 general-purpose corridor reports generated
from the observation-coverage run
`tmc-observation-coverage-2026-08-19-12-31`, its final TAPlite assignment, and
the corridor measurement run
`corridor-profile-measurement-2026-08-19-15-17`.

## Published contents

- Interactive corridor map and selector
- Corridor performance statistics
- Projection figures
- Daily speed, volume, and model-comparison figures
- A separate corridor profile measurement page with downloadable results
- One embedded report page for each corridor

This repository contains published dashboard artifacts only. The processing
source code, input datasets, intermediate files, and full run outputs remain in
the private NVTA project repository.

GitHub Actions deploys every commit to `main` to GitHub Pages. A companion
workflow in `NVTA_internal` synchronizes the latest completed integrated
dashboard into this repository whenever its `main` branch changes.
