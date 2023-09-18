# Use a base image (e.g., Alpine Linux) with Java
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /scouter

# Copy your local Scouter files to the container
COPY /scouter /scouter/

# Expose the Scouter server port (default is 6100)
EXPOSE 6100

# Start Scouter
ENTRYPOINT ["tail", "-f", "/dev/null"]