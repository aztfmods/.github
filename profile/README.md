## Welcome 👋
This space contains a collection of terraform repositories dedicated to azure cloud. These codebases contain  
reliable and production-grade modules that will allow you to easily create workloads or projects in Azure.  

This approach is particularly useful for teams that are embracing open source processes and seeking to work  
more efficiently through innersourcing strategies.

### Standards:

* [Semantic versioning](https://semver.org/) is applied based on branch name.
* The [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification is enforced.
* [Probot apps](https://probot.github.io/docs/development/) are used to orchestrate github settings
* Release PRs are used to generate releases and tags.
* Various linting and validation is applied before merging to the main branch.
* Reusable workflows are used.
* Dependencies are updated using dependabot.

### Principles:

* No big monolith codebase for modules.
* Consistent [resource naming](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming) is applied using azure-compliant [abbreviations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations).
* Modules are feature rich, documented, validated and tested.
* Modules contain logical grouped resources and have their own lifecycle.
* Modules contain various integrations and provide example usage.
