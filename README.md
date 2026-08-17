# Could Manhattan Have Superblocks?

A data-driven search for Barcelona-style superblock candidate sites in the Manhattan street grid.

*Urban Data Analysis — KAIST Exchange, Fall 2026 (NYU)*

## Summary

Screens the Manhattan street grid for structural feasibility of Barcelona-style
superblocks, using real data from OpenStreetMap, NYC DOT, MTA, NYC DCP, and the
US Census. Of 6,241 candidate units generated, **1,484 (23.8%) survive** hard
exclusion — mainly ruled out by interior bus routes (70.6%) and truck routes
(51.3%), not traffic volume. The resulting ranking is stable (Spearman
correlation 0.87–0.98) across alternative scoring weights.

## Contents

- `notebooks/project_proposal_YerinEun.ipynb` — initial project proposal (research question, dataset plan, methodology)
- `notebooks/project_final_YerinEun.ipynb` — final notebook: real API data pipeline, four-part analysis (exclusion, suitability scoring, sensitivity, disruption assessment), and discussion
- `slides/` — proposal and final presentation decks (.pptx)

## Key reference

Eggimann, S. (2022). The potential of implementing superblocks for
multifunctional street use in cities. *Nature Sustainability*, 5, 406–414.

## Tools

`osmnx`, `networkx`, `geopandas`, `shapely`, `pandas`, `numpy`, `requests`,
`matplotlib`, `scipy`
