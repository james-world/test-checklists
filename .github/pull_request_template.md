# PR Checklist

To be completed in the PR review. *Note that links will open in same tab unless you ctrl-click them or similar. This is a github limitation.*

- [ ] The purpose of the PR is clear, and it has been tested to work locally or in CI as far as possible.
- [ ] Changes are cleanly separated into distinct [properly named commits](https://imburse.atlassian.net/wiki/spaces/DEV/pages/523665529/Commit+Messages), each with a clear comment and purpose.
- [ ] Unit and integration tests have been added to provide appropriate coverage of the committed changes. Reliance on end-to-end tests has been minimised.
- [ ] The README.md has been updated to reflect any changes to infrastructure, support playbooks, DataDog dashboards, external dependencies, published contracts (e.g. shared nuget packages), APIs and Information Models (e.g. database schema)
- [ ] [Logging Standards](https://imburse.atlassian.net/wiki/spaces/DEV/pages/592281609/Observability+Standards) have been followed.
- [ ] The affect on performance and scalability has been considered. Basic checks on resource consumption and latency have taken place locally and the need for any performance testing in the load environment is in a referenced ticket on the backlog.
- [ ] Security has been considered. New APIs have appropriate access controls. Network communications and data at rest are appropriately protected.
