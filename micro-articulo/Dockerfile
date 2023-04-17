FROM openjdk:20-ea-17-jdk
VOLUME /tmp
EXPOSE 9091
ADD ./build/libs/micro-articulo-0.0.1-SNAPSHOT.jar micro-articulo.jar
ENTRYPOINT [ "java", "-jar", "micro-articulo.jar" ]