FROM lolhens/baseimage-openjre:latest
ADD target/springbootApp.jar springbootApp.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "springbootApp.jar"]
