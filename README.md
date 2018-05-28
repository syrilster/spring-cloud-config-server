**Problem Statement:** As an application moves through the deployment pipeline from dev to test and into production you can manage the configuration between those environments and be certain that applications have everything they need to run when they migrate.

* This is a micro service which maintains all the project related properties in a centralized manner.
* This service stores all the configs in a remote git repository.
* REST endpoints are available for other services to consume the values.
* @EnableConfigServer annotation is used.

![spring-cloud-config-server](https://user-images.githubusercontent.com/6800366/40424943-98fa4c6e-5eb4-11e8-88cd-f2785b578568.PNG)

