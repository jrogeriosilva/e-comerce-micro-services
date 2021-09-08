
#  Microservices architecture
Building a project with microservices architecture using Spring Cloud.

##
### Microservices
* Config Server (Requesting configuration Files [Here](https://github.com/jrogeriosilva/micro-services-config))
* Gateway
* product-catalog
* service discovery

## Preparing the Development environment

Install Docker Compose
You can run Compose on macOS, Windows, and 64-bit Linux.

https://docs.docker.com/compose/install/

### Run Docker Compose

```console
docker-compose up -d
```

## Redis and Elasticsearch




### Used Tecnologies
* Docker 19.3.15
* Docker compose 1.29.2
* Java OpenJDK 16
* Gradle
* Spring Boot 2.5.2


### Health
To check the services health, go to:
http://localhost:8080/actuator/health

and see the output:
```json
{ "status" : "UP" }
```
