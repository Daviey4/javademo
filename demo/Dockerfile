# Use a base image with OpenJDK
FROM openjdk:11-jdk

# Set the working directory inside the container
WORKDIR /demo

# Copy the compiled JAR file into the container
COPY Main.java Main.java

# Expose port 8080 for the application
EXPOSE 8080

# Command to run the application
CMD [ "java", "Main.java" ]
