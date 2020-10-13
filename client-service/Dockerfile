FROM adoptopenjdk:11-jre-hotspot
COPY build/libs/client-service-0.0.1-SNAPSHOT.jar service.jar
CMD java $JAVA_OPTS -jar /service.jar $ARGS
EXPOSE 8080
