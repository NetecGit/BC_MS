FROM openjdk:20-ea-17-jdk
VOLUME /tmp
EXPOSE 9099
ADD ./build/libs/micro-eureka-0.0.1-SNAPSHOT.jar micro-eureka.jar
ENTRYPOINT [ "java", "-jar", "micro-eureka.jar" ]