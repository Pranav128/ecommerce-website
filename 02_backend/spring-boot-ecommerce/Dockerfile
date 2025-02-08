FROM openjdk:18
WORKDIR /app
COPY /target/spring-boot-ecommerce-0.0.1-SNAPSHOT.jar /app/spring-boot-ecommerce-0.0.1-SNAPSHOT.jar
EXPOSE 8080
#CMD ["java", "-jar", "Eazy-School-web-application-0.0.1-SNAPSHOT.jar"]
ENTRYPOINT ["java", "-jar", "spring-boot-ecommerce-0.0.1-SNAPSHOT.jar"]

#FROM openjdk:18
#COPY target/spring-boot-ecommerce-0.0.1-SNAPSHOT.jar /app.jar
#EXPOSE 8080
#ENTRYPOINT ["java", "-jar", "/app.jar"]