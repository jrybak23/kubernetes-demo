FROM openjdk:11-jre
WORKDIR /app
ADD target/service-b.jar /app
CMD ["java", "-jar", "-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005", "service-b.jar"]