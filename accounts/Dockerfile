FROM adoptopenjdk:8

COPY ./target/account-docker-file.jar account-docker-file.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "account-docker-file.jar"]