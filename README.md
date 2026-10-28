# Aethmodular graph gallery

GitHub Pages site for the interactive gallery in [ahzs645/aethmodular](https://github.com/ahzs645/aethmodular)
(`gallery/`). **Live page:** https://projects.ahmadjalil.com/aethmodular-gallery/

Latest successful publication: [aethmodular `72c4e83f06939839f2109459d1043aa4d416336e`](https://github.com/ahzs645/aethmodular/commit/72c4e83f06939839f2109459d1043aa4d416336e)
with [data snapshot `data-76de70a83606`](https://github.com/ahzs645/aethmodular-gallery/releases/tag/data-76de70a83606).
[Deployment run](https://github.com/ahzs645/aethmodular-gallery/actions/runs/40788968737).

Published with `gallery/share/publish_pages.py`: the data (`gallery/app/public/data`, machine paths
scrubbed) is a release of this repo (`data-<hash>`, asset `gallery-data.tar.gz`), and
`.github/workflows/deploy.yml` builds the site from the source repo at a pushed commit and deploys it,
started by `workflow_dispatch` or by a push to `main` that changes `deploy-request.json`.
The files on `main` from before October 2026 are an earlier static build, kept as a fallback
(`publish_pages.py --branch`); Pages no longer serves them.

## Data

Filter chemistry and FTIR/HIPS work on SPARTAN sites and the IMPROVE network. Several tabs (Meeting,
Calibration, Baselines, Spectral similarity, Blanks) show work in progress on FTIR elemental-carbon
calibration for Addis Ababa; numbers there are preliminary.

- IMPROVE data: please cite Malm et al. (1994), J. Geophys. Res. 99, 1347-1370, and see the IMPROVE
  data advisories (http://vista.cira.colostate.edu/IMPROVE/Data/QA_QC/Advisory.htm).
- SPARTAN data: see https://www.spartan-network.org for data use and citation.
