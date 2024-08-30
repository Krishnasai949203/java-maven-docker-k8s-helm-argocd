FROM maven:3.8.5-openjdk-11-slim
WORKDIR /app
COPY pom.xml /app
COPY src ./src
RUN mvn clean package 
