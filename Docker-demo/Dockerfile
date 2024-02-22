FROM openjdk:21
LABEL maintainer="github.com/AlexGens"
WORKDIR /app
ADD target/docker-demo-1.0.0.jar /app/app.jar
ENTRYPOINT ["java","-jar","/app/app.jar"]
EXPOSE 8000
