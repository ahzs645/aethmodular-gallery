# Aethmodular graph gallery

GitHub Pages site for the interactive gallery in [ahzs645/aethmodular](https://github.com/ahzs645/aethmodular)
(`gallery/`). **Live page:** https://projects.ahmadjalil.com/aethmodular-gallery/

Latest successful publication: [aethmodular `cb2e1469ec222719c347b9b5f672765ede3ed7c7`](https://github.com/ahzs645/aethmodular/commit/cb2e1469ec222719c347b9b5f672765ede3ed7c7)
with [data snapshot `data-82d701248232`](https://github.com/ahzs645/aethmodular-gallery/releases/tag/data-82d701248232).
[Deployment run](https://github.com/ahzs645/aethmodular-gallery/actions/runs/42243757969).

Published with `gallery/share/publish_pages.py`: the data (`gallery/app/public/data`, machine paths
scrubbed) is a release of this repo (`data-<hash>`, asset `gallery-data.tar.gz`), and
`.github/workflows/deploy.yml` builds the site from the source repo at a pushed commit and deploys it.
The files on `main` from before October 2026 are an earlier static build, kept as a fallback
(`publish_pages.py --branch`); Pages no longer serves them.

## Closeout review candidate

The [7 November closeout candidate record](docs/closeout-candidate-2026-11-07.md) identifies the corrected data archive, its verified Google Drive preservation, and the corresponding source and verification records. Its suggested data tag is `data-accc09aa8eea`; it remains unpublished and is not the live deployment. The record preserves the original `data-82d701248232` base separately for the verified base-plus-overlay review workflow.

## Data

Filter chemistry and FTIR/HIPS work on SPARTAN sites and the IMPROVE network. Several tabs (Meeting,
Calibration, Baselines, Spectral similarity, Blanks) show work in progress on FTIR elemental-carbon
calibration for Addis Ababa; numbers there are preliminary.

- IMPROVE data: please cite Malm et al. (1994), J. Geophys. Res. 99, 1347-1370, and see the IMPROVE
  data advisories (http://vista.cira.colostate.edu/IMPROVE/Data/QA_QC/Advisory.htm).
- SPARTAN data: see https://www.spartan-network.org for data use and citation.
