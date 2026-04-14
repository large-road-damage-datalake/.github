# Contributing

Thanks for your interest in improving the **Large Road Damage Datalake** organization.

This organization publishes **dataset repositories** that focus on structured information for each dataset (metadata, computed statistics, representative samples/visualizations, and publication documentation). **We do not aim to mirror full raw datasets inside these repositories**; original sources and licensing constraints should be documented clearly in each dataset repo (see `DOWNLOAD.md`).

## Where to start
- **Questions / open discussion**: [GitHub Discussions](https://github.com/orgs/large-road-damage-datalake/discussions)
- **Concrete fixes** (broken links, incorrect metadata/stats, packaging problems): GitHub Issues

## Dataset template (required baseline)
New dataset repositories should follow the organization template:

- [`dataset-template`](https://github.com/large-road-damage-datalake/dataset-template)

The template defines the expected structure and tooling for generating consistent artifacts (including validation helpers).

## What we expect in every dataset repository
At minimum, keep the publication-facing artifacts consistent and complete. Typically this includes:

- `METADATA.json` (stable keys; do not rename fields without a coordinated migration)
- `stats/` outputs used by the website (do not “hand edit” generated JSON unless you are fixing a documented bug and can reproduce the fix)
- `visualizations/` outputs used for previews (same rule: prefer regenerating via the template pipeline)
- Publication docs: `README.md`, `ABSTRACT.md`, `SUMMARY.md`, `CITATION.md` / `CITATION.bib`, `DOWNLOAD.md`, `LICENSE.md`

If you change metadata shape, treat it like an API change: update **all** affected dataset repos or provide a compatibility plan.

## Licensing, attribution, and redistribution
Contributions must respect upstream rights.

- Include accurate **attribution** and **citation** information.
- Make the **license** explicit in `LICENSE.md` and consistent with `METADATA.json`.
- In `DOWNLOAD.md`, clearly separate:
  - **Original source** location and terms
  - **This repository** (what it contains / what it does not mirror)

Do not contribute material you do not have the rights to redistribute.

## Privacy and sensitive data
- Avoid committing secrets (tokens, private endpoints, personal data).
- Avoid publishing sensitive geolocation or other identifiers unless permitted and intentional.

## Pull request guidelines
- Keep changes focused: one logical change per PR when possible.
- If stats/visualizations change, explain **why** (pipeline change, bugfix, upstream correction).
- If metadata keys change, explain **migration impact** for consumers (e.g., website rendering).

## Code of conduct
Please read [`CODE_OF_CONDUCT.md`].

## Security
If you believe you’ve found a security vulnerability, please read [`SECURITY.md`](https://github.com/large-road-damage-datalake/.github/blob/main/SECURITY.md) and do not post it publicly.
