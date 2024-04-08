FROM openjdk:17

# Set the working directory in the Docker container
WORKDIR /app

# Copy the .jar file from your host to your image's working directory
COPY ./test-1.jar test-1.jar

# The CMD instruction can include multiple system properties
CMD ["java", "-jar" , "test-1.jar"]