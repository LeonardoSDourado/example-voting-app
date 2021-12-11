FROM maven:3.6.1-jdk-8-alpine

WORKDIR /app

COPY . .

RUN mvn compile

RUN mvn test

RUN mvn package -DskipTests
