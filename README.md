# Spring Standalone service
With Spring Boot you can run a Rest service embedded in you app.
This allows for a very simple streamlined way to build your RESTful API.

# Demo
Make sure you are using maven 3.0+

Just run
```
mvn spring-boot:run
```

Open http://localhost:8080/greeting in your browser

# Create Uber JAR
Just run
```
mvn clean package
```

Size of the JAR 13MB

Run your server
```
java -jar target/gs-rest-service-0.1.0.jar
```



# References

# Spring documentation
https://spring.io/guides/gs/rest-service/

# Notes
* Make sure you run it with Maven3
* No XML
* Small footprint 13MB