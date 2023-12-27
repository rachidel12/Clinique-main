FROM openjdk:17-jdk-alpine
WORKDIR /opt
ENV PORT 9093
COPY target/*.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar