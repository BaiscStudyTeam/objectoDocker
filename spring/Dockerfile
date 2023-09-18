# Use an appropriate base image with Java (e.g., OpenJDK 17)
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app

# Copy your application JAR file and Scouter agent to the container
COPY objecto.jar /app
COPY deploy-config.yml /app

# Define the CMD to start your application
 CMD ["sh", "-c", "java -jar /app/objecto.jar"]
# ENTRYPOINT ["tail", "-f", "/dev/null"]