
#  Microservices architecture
Building a project with microservices architecture using Spring Cloud.
![2021-09-08](https://user-images.githubusercontent.com/15113099/132511714-0bcf1a19-bb66-4fc0-a72d-e41081302adf.png | width=100)

##
### Microservices
* Config Server (Requesting configuration Files [Here](https://github.com/jrogeriosilva/micro-services-config))
* Gateway
* product-catalog
* service discovery


### Used Tecnologies
* Docker
* Java OpenJDK
* Gradle
* Spring Boot
* ElasticSearch
* Redis


## Preparing the Development environment

Install Docker Compose
You can run Compose on macOS, Windows, and 64-bit Linux.

https://docs.docker.com/compose/install/

### Run Docker Compose

```console
docker-compose up -d
```


### Health
To check the services health, go to:
http://localhost:8080/actuator/health

and see the output:
```json
{ "status" : "UP" }
```
