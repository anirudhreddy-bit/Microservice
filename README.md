# Springboot-Microservice
Springboot-Microservice
●	Implemented using Spring Boot, Service Registry, API Gateway, Hystrix Dashboard, Cloud Config Server, Zipkin and Sleuth Logging.
●	 Service Registry- To get the network location of a service instance we connect all the services to the Service Registry.
●	API Gateway- It acts as a reverse proxy to accept all application programming interface (API) calls, aggregate the various services required to fulfill them and return the appropriate result.
●	Hystrix Dashboard- provides benefits to monitoring the set of metrics on a dashboard. It displays the health of each circuit-breaker in a very simple way.
●	Cloud Config Server-   instead of configuring all the services of same configurations we use git repo and get the default configurations and also it is easy to change the configurations.
●	Zipkin and Sleuth Logging- By using the distributed log tracing we can identify from which services the request is called and what is the trace id and this trace id will be the unique trace id across all the services and there is a span id  the span id changes according to to the microservices so that we can know the traversal of a request where it was failed and success
