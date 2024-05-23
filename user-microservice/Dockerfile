FROM openjdk:17-oracle
VOLUME /tmp
COPY target/*.jar user-microservice.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/user-microservice.jar"]