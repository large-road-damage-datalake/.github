# Large Road Damage Datalake

A curated catalog of road-surface damage datasets (cracks, potholes, and related distress types) organized for consistent discovery, comparison, and reuse across computer-vision research projects.

## What this organization is
- **Purpose**: Keep dataset information in one place with a consistent structure and clear metadata.
- **What’s included**: Dataset pages with structured metadata, computed stats, and representative samples/visuals.
- **What’s not included**: The full raw datasets are typically hosted by their original sources and linked from each dataset repository.

## What you’ll find here
- **Dataset repositories**: One repository per dataset, focused on a detailed, comparable dataset view.
- **A consistent set of artifacts** (varies slightly by dataset):
  - Publication docs: `README.md`, `ABSTRACT.md`, `SUMMARY.md`, `CITATION.*`, `DOWNLOAD.md`, `LICENSE.md`
  - Structured metadata: `METADATA.json`
  - Computed analytics: `stats/`
  - Sample visualizations: `visualizations/`

## Downloads and original sources
Each dataset repository includes a `DOWNLOAD.md` describing:
- where the original dataset comes from
- how to obtain it (when available)
- license and usage constraints
- any notes needed to reproduce the packaged statistics and samples

## Reproducible dataset packaging
To reproduce a dataset repository in this organization, start from:

- Template: @dataset-template

It provides the same folder structure and scripts used to generate metadata, stats, and sample visualizations, along with validation helpers.

## Trust signals
- **Licensing & attribution** are surfaced in each dataset repository.
- **Metadata keys** are kept stable so dataset pages render reliably.
- **Stats and samples** are generated through a defined pipeline.
