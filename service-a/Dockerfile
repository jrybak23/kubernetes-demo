FROM openjdk:11-jre
WORKDIR /app
ADD target/service-a.jar /app
CMD ["java", "-jar", "-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005", "service-a.jar"]