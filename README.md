# Integrating cloud into research CI

Many research software teams are constrained by their existing CI implementations. In particular, hardware infrastructure often falls far short of providing a reliable service or a service that can handle growing demands for testing as a project progresses. Performance testing may require very large problems to be run occasionally on high-end platforms with known, reliable performance characteristics, which don't conform to standard CI workers. CI instances may only be accessable from one institution, restricting information flow between collaborators. Using available comercial hosted services may not be an option where research software has particular requirements that do not fit well into standard software development models.

Integrating cloud resources into existing CI, or moving an entire CI infrastructure into the cloud whilst maintaining heavy customisations, can remove existing constraints. However, the often quite unusual and demanding requirements of research software projects may not be well served by existing documentation on cloud CI deployment, and the knowledge barrier to entry can be prohibitively high.

## Sprint objectives

Taking the example of [Jenkins](https://jenkins.io/) as a widespread research CI platform, create learning resources to teach:

* Integration of Azure cloud resources into an existing Jenkins instance
  * Understanding of how to manage and monitor incurred costs from on-demand deployments
  * Learning how to replicate a cloud environment locally to debug failures
* Customised deployment of Jenkins with AKS
  * Understanding the capabilities and limitations of AKS for research CI jobs
* Using cloud resources for effective and efficient performance testing of large tests

## Learning prerequisites

* [Jenkins on Azure](https://docs.microsoft.com/en-us/azure/jenkins/)
* [Docker on Azure](https://azure.microsoft.com/en-us/services/kubernetes-service/docker/)
* [Jenkins with Docker](https://jenkins.io/doc/book/pipeline/docker/)
