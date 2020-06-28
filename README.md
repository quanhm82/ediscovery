# Getting Started

### Introduction
eDiscovery is an Eureka server and required to start ahead all other services. 

### Guides
Building jar file by maven
```sh
$ mvn clean install
```
Starting eDiscovery instance with "dev" profile
```sh
$ cd target
...
$ java -jar ediscovery-{version}.jar -Dspring.profile.active=dev
```
Access eDiscovery by http://localhost:8761