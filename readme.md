# Spring REST Webservice

### About
A simple REST client, that consumes a JSON object from a REST Web Service.

### Techstack
* Java 11
* Spring Boot : 2.4.4
* Jackson
* Maven Wrapper
* Spring Initializer : https://start.spring.io/
* Tomcat

### Usage
```sh
./mvnw spring-boot:run
```


The Rest client uses the REST Web Service on https://quoters.apps.pcfone.io/api/random and 
responds with a String representing a consumed JSON from the given REST Web Service as a console log message:

```
Quote{type='success', value=Value{id=7, quote='The real benefit of Boot, however, is that it's just Spring. That means any direction the code takes, regardless of complexity, I know it's a safe bet.'}}
```

---

based on:

* https://spring.io/guides/gs/consuming-rest/
* https://start.spring.io/