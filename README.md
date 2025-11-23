# Distributed Tracing with OpenTelemetry and Jaeger

In this project I have figured out how we can integrate distributed tracing in a Spring Boot application. 
We are using OpenTelemetry to export traces to Jaeger.

this service is called by [service 1](https://github.com/ngnawensv/distributed-tracing-opentelemetry-jaeger-service1/tree/master). Make sure both services are started.

Make sure you the `docker-compose.yaml` with command `docker-compose up`

This serviceonsume fake API [{JSON} Placeholder](https://jsonplaceholder.typicode.com/)

Follow this link to monitor your traces [http://localhost:16686/search](http://localhost:16686/search)



