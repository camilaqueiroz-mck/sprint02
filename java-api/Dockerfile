# Set an image
FROM eclipse-temurin:17-jdk-jammy

# Copy jar file
COPY target/java-api-0.0.1-SNAPSHOT.jar /app/target

WORKDIR /app

# run the app
ENTRYPOINT ["java", "-jar", "java-api-0.0.1-SNAPSHOT.jar"]

EXPOSE 8000 