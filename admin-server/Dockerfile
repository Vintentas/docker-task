FROM adoptopenjdk:11-jre-hotspot
COPY build/libs/admin-server-0.0.1-SNAPSHOT.jar service.jar
CMD java $JAVA_OPTS -jar /service.jar $ARGS
EXPOSE 9003
