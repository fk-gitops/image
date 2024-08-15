# Pull base image
FROM nginx:1.27

# Dockerfile Maintainer
LABEL MAINTAINER Fernando "fkarnagi@gmail.com"

# Install mvn
RUN apt update && apt install -y openjdk-17-jre-headless && apt install -y maven
RUN java -version
RUN mvn -version