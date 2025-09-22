# Data & Storage

Use this page to keep track of every dataset used in the Historic Biodiversity & Human Infrastructure sprint. Add links as soon as you adopt a source so teammates know where to find it and what preparation steps are required.

## Quick links
- **Group 5 CyVerse folder:** [i:/iplant/home/shared/esiil/Innovation_summit/Group_5](https://de.cyverse.org/data/ds/iplant/home/shared/esiil/Innovation_summit/Group_5)
- **Shared code repository:** [code/ directory](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/tree/main/code)
- **Working notes:** [documentation/group-notes.md](https://github.com/CU-ESIIL/historic-biodiversity-human-infrastructure-innovation-summit-2025__5/blob/main/documentation/group-notes.md)

## Datasets in play
| Dataset | Description | Access / Path | Notes |
|---------|-------------|---------------|-------|
| GBIF historic occurrences | Filtered occurrences (1900–present) for focal taxa within the study area. | `Group_5/shared_data/gbif_occurrences/` | Export as CSV + GeoJSON; include citation metadata. |
| Land cover & habitat connectivity | NLCD, USGS PAD-US cores, and connectivity rasters for fragmentation analysis. | `Group_5/shared_data/habitat_connectivity/` | Large rasters — sync via `gocmd` with `--diff`. |
| Transportation & energy corridors | NTAD transportation layers plus EIA transmission corridors. | `Group_5/shared_data/infrastructure_corridors/` | Document version/date in README. |
| Community & stewardship layers | Tribal lands, conservation easements, and community-identified priority sites. | `Group_5/shared_data/community_layers/` | Confirm sharing permissions before publishing maps. |

Add rows as you incorporate new data. If a dataset lives outside CyVerse, include the public URL and note authentication requirements.

## Handling sensitive or large data
- Keep raw downloads in CyVerse rather than GitHub. Use lightweight samples if you need to demonstrate structure in this repo.
- Record any restrictions (e.g., license, data sharing agreements) directly in the table above.
- When generating outputs, save deliverables to `Group_5/outputs/` with timestamps so others can trace your workflow.

## Reproducibility checklist
- [ ] Each dataset listed above includes a pointer to the exact file or folder location.
- [ ] Processing scripts in `code/` mention required inputs/outputs in their docstrings or README entries.
- [ ] Visuals on the homepage cite the data sources that produced them.

Keeping this page current helps external reviewers and future teammates understand how to rebuild the analysis.
