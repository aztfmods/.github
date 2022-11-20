## Welcome 👋
This space contains a collection of terraform repositories dedicated to azure cloud. With the help of this codebase, it will be  
possible to quickly create workloads or projects using reliable, tested and production-grade terraform modules.

This approach is ideal for teams that are adopting open source processes in order to work and collaborate more  
effectively using innersourcing strategies.

### Standards:

* [Semantic versioning](https://semver.org/) is applied based on branch name.
* The [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification is enforced.
* Release PRs are used to generate releases and tags.
* Various linting and validation is applied before merging to the main branch.
* Reusable workflows are used.
* Dependencies are updated using dependabot.
* Github settings are managed by probot apps

### Principles:

* No big monolith codebase for modules.
* Consistent [resource naming](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming) is applied using azure-compliant [abbreviations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations).
* Modules are feature rich, documented, validated and tested.
* Modules contain logical grouped resources and have their own lifecycle.
* Modules contain various integrations and provide example usage.
