FROM ubuntu:latest
RUN apt-get update && apt-get install -y \
    git \
    openjdk-17-jdk
RUN wget https://services.gradle.org/distributions/gradle-7.4.2-bin.zip -P /tmp \\
    && unzip gradle-7.4.2-bin.zip -d /opt \\
    && rm gradle-7.4.2-bin.zip
ENV GRADLE_HOME=/opt/gradle-7.4.2