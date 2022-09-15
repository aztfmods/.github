## Welcome 👋
This space is a collection of terraform repositories dedicated to azure cloud.
After applying a framework like [caf enterprise scale](https://github.com/Azure/terraform-azurerm-caf-enterprise-scale)
there is a need to easily create workloads or projects using modules.

### Principles:

* Each module contains one or more logical resources grouped together.
* [Semantic versioning](https://semver.org/) is used based on branch name.
* Before merging to the main branch there is required validation that must succeed.
* Release PRs are used to generate releases and tags.
* Various linting will be enforced.
* Each module contains multiple integration examples, which can be tested.