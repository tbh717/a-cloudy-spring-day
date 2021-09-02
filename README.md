# a-cloudy-spring-day

### Running Locally
Without containerizing the application, you can run locally using the command `./mvnw package && java -jar target/a-cloudy-spring-day-0.0.1.jar`

### Building Locally
1. Containerize the application using the command `docker build -t springio/a-cloudy-spring-day .`
2. You can then run the container locally using the command `docker run -dp 8080:8080 springio/a-cloudy-spring-day`