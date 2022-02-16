FROM openjdk:8
# Set working directory
WORKDIR /usr/app
# Copy jar file to WORKDIR
COPY ./target/spring-boot-data-mongodb-0.0.1-SNAPSHOT.jar .
# Listen on port 8080
EXPOSE 8080
# Excute jar file
CMD ["java", "-jar", "spring-boot-data-mongodb-0.0.1-SNAPSHOT.jar"]
