# Contributing

Thanks for your interest in improving the **Large Road Damage Datalake** organization.

This organization publishes **dataset repositories** focused on structured dataset information: metadata, computed statistics, representative samples/visualizations, and publication documentation. Original datasets are obtained under their upstream terms and are documented per repository in `DOWNLOAD.md`.

## How to participate
- **Questions and open-ended discussion**: [GitHub Discussions](https://github.com/orgs/large-road-damage-datalake/discussions)
- **Actionable fixes** (incorrect metadata/stats, broken links, packaging/validation problems): GitHub Issues

## Dataset template
New dataset work should follow the organization template repository:

- [`dataset-template`](https://github.com/large-road-damage-datalake/dataset-template)

## Expectations for dataset repositories
Keep publication-facing artifacts consistent, complete, and reproducible:

- `METADATA.json` with stable field names
- Generated outputs in `stats/` and `visualizations/` (prefer regenerating via the template pipeline rather than manual edits)
- Publication docs: `README.md`, `ABSTRACT.md`, `SUMMARY.md`, `CITATION.md` / `CITATION.bib`, `DOWNLOAD.md`, `LICENSE.md`

Treat changes to `METADATA.json` like a compatibility contract: coordinate updates across affected repositories when field meanings or required keys change.

## Licensing, attribution, and redistribution
- Provide accurate **attribution** and **citation** information.
- Keep `LICENSE.md` aligned with the license described in `METADATA.json`.
- In `DOWNLOAD.md`, clearly document the **original source**, how it is obtained, and any usage constraints.

## Privacy and repository hygiene
- Do not commit secrets, credentials, or private endpoints.
- Do not add sensitive personal data unless it is explicitly required and permitted.

## Pull requests
- Prefer focused changes with a clear rationale.
- When stats or visualizations change, include a short note explaining what changed in the pipeline or upstream inputs.
- When metadata changes, include a short note explaining consumer impact.

## Code of conduct
This organization uses the **Contributor Covenant** code of conduct:

- [`Contributor Covenant 2.1`](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)

## Security
Report security issues using [`SECURITY.md`](https://github.com/large-road-damage-datalake/.github/blob/main/SECURITY.md). Do not post undisclosed vulnerabilities in public Issues or Discussions.
