# snnLab Project - Config Server Management

* This project provides cloud config server capabilities into snnLab microservices.
* Spring Cloud Config is used for server capabilities.
* All microservice configurations in snnLab Project are handled on one GitHub repository, namely, "snnlab-microservice-config" and each config file name pattern is  {spring.application.name}-{spring.profiles.active}.yml
* In case of lab experimental project , only one repository is used and default profiles are selected.
* Authentication properties is disabled.

# Technologies

* Spring Cloud Config Server
