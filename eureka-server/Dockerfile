FROM openjdk:17-oracle
VOLUME /tmp
COPY target/*.jar eureka-server.jar
ENTRYPOINT ["java","-jar","/eureka-server.jar"]