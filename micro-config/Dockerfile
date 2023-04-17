FROM openjdk:20-ea-17-jdk
VOLUME /tmp
EXPOSE 9102
ADD ./build/libs/micro-config-0.0.1-SNAPSHOT.jar micro-config.jar
ENTRYPOINT [ "java", "-jar", "micro-config.jar" ]