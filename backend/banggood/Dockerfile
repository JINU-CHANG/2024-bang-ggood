FROM openjdk:17
COPY build/libs/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar", "0.0.0.0:8080"]
