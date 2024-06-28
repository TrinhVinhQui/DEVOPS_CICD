FROM openjdk:8u151-jdk-alpine3.7
WORKDIR $APP_HOME
#EXPOSE 8070

#ENV APP_HOME /usr/src/app
#ENTRYPOINT exec java -jar app.jar
# Use an official OpenJDK runtime as a parent image
#FROM openjdk:11-jre-slim

# Set the working directory in the container
#WORKDIR /app

# Copy the JAR file into the container at /app
COPY target/shopping-cart-0.0.1-SNAPSHOT.jar app.jar

# Make port 8080 available to the world outside this container
EXPOSE 8070

# Run the jar file
ENTRYPOINT ["java","-jar","app.jar"]
