FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /
ENTRYPOINT ["java","-jar","/user-service.jar"]
EXPOSE 9002