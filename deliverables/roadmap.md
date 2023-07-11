# conda-forge's roadmap to sustainable infrastructure

The CZI EOSS 5 grant assigned to conda-forge has the long-term sustainability of conda-forge at the core of its proposal. We believe that sustainability is a multi-faceted problem that, in the case of conda-forge, requires work on the following areas:

- **Infrastructure**: conda-forge's automation and infrastructure needs to be improved to make it more robust and easier to maintain.
- **Documentation**: many areas of conda-forge operate with no documentation beyond the code itself and the knowledge of a few key contributors.

This document is a living document that will be updated as the grant progresses. It is meant to be a high-level overview of the work that is being done and the work that is planned to be done.

## Themes

In order to be sustainable, conda-forge's infrastructure...

* needs to be fully documented and up-to-date.
* should be easier to test and debug.
* should be more robust to failures, and it should be easier to recover from failures.
* should have better control over its dependencies supply chain.
* should auto-report failures to the right people.
* should be as secure as reasonably possible.

### Documentation

* Start a [Docusaurus project](#) to document conda-forge's infrastructure. This will double as an experiment to replace conda-forge.org's documentation with a more modern documentation system.
* Enumerate the different infrastructure pieces and document them.
* Provide guides for new contributors to get started with conda-forge's infrastructure.

> In general, for all new documentation that is written for conda-forge (not necessarily about infrastructure), we neeed to ensure that there are clearcontribution guidelines so the same mistakes are not made in the future.

### Security 

* Audit the existing infrastructure for potential security issues, following a PASTA-like methodology.
* Create a report of found issues and share it confidentially with the core team.
* Fix the issues that are found to be important.

### Infrastructure

* Refactor libcfgraph and cf-graph-countyfair database repositories.
* Add a testing suite to the regro bots.
* Add failure reports.
* Add mechanisms to prevent errors from supply chain updates.
