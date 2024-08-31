FROM maven:3.8.5-openjdk-11-slim
USER root
RUN apt-get update && apt-get install -y docker.io
WORKDIR /app
COPY pom.xml /app
COPY src ./src
RUN mvn clean package 
