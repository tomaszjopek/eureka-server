FROM openjdk:11
COPY ../target/eureka-server-0.0.1-SNAPSHOT.jar /eureka-server.jar
EXPOSE 8761
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=dev", "/eureka-server.jar"]