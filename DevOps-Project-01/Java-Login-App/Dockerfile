FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY target/*.jar app.war

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.war"]
