# Use a base image with Docker pre-installed
FROM docker:latest

# Install OpenJDK and Maven
RUN apk --no-cache add openjdk11 maven

# Set environment variables for Maven
ENV JAVA_HOME=/usr/lib/jvm/default-jvm
ENV PATH=${JAVA_HOME}/bin:${PATH}
