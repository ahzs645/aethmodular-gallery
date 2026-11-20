# Aethmodular graph gallery

GitHub Pages site for the interactive gallery in [ahzs645/aethmodular](https://github.com/ahzs645/aethmodular)
(`gallery/`). **Live page:** https://projects.ahmadjalil.com/aethmodular-gallery/

Latest successful publication: [aethmodular `a997ac0bc65cc3d04bce2b169102a1ae27bd2b6e`](https://github.com/ahzs645/aethmodular/commit/a997ac0bc65cc3d04bce2b169102a1ae27bd2b6e)
with [data snapshot `data-19371073fd5d`](https://github.com/ahzs645/aethmodular-gallery/releases/tag/data-19371073fd5d).
[Deployment run](https://github.com/ahzs645/aethmodular-gallery/actions/runs/44832094801).

Published with `gallery/share/publish_pages.py`: the data (`gallery/app/public/data`, machine paths
scrubbed) is a release of this repo (`data-<hash>`, asset `gallery-data.tar.gz`), and
`.github/workflows/deploy.yml` builds the site from the source repo at a pushed commit and deploys it.
The files on `main` from before October 2026 are an earlier static build, kept as a fallback
(`publish_pages.py --branch`); Pages no longer serves them.

## Data

Filter chemistry and FTIR/HIPS work on SPARTAN sites and the IMPROVE network. Several tabs (Meeting,
Calibration, Baselines, Spectral similarity, Blanks) show work in progress on FTIR elemental-carbon
calibration for Addis Ababa; numbers there are preliminary.

- IMPROVE data: please cite Malm et al. (1994), J. Geophys. Res. 99, 1347-1370, and see the IMPROVE
  data advisories (http://vista.cira.colostate.edu/IMPROVE/Data/QA_QC/Advisory.htm).
- SPARTAN data: see https://www.spartan-network.org for data use and citation.
