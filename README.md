# HoursXML
 Simple repo to manage the hours xml we publish for passport hours display

## Ownership and GitHub workflow

Owner: **Justin Nunn (`@skyparkjustin`), SkyPark IT/AV**.
Canonical repository: [spsvent/HoursXML](https://github.com/spsvent/HoursXML).
Default branch: `main`; work in a separate issue branch.

Read [the clone setup and PR workflow](docs/GITHUB-WORKFLOW.md) and enable the
reviewed identity guards with `sh tools/install-git-hooks.sh` (Python 3 required).
Preserve any existing hooks. Leave notes in [docs/handoffs](docs/handoffs/README.md).

This baseline does not enable server-side branch protection, rotate secrets, or
verify deployment health. Those remain tracked in spsvent/SkyPark#101.
