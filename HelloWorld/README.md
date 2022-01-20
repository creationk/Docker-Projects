# Build a Docker image using Maven and SpringBoot

1. Using the integrated Spring Boot build-image goal

mvn spring-boot:build-image
(Dockerfile will be ignored)

2. Using the dockerfile-maven-plugin from Spotify

mvn package