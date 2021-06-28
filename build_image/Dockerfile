FROM openjdk:11-jdk
RUN apt-get update
RUN apt-get -y install maven git docker.io
ADD .ssh/id_rsa /root/.ssh/id_rsa
RUN chmod 600 /root/.ssh/id_rsa
RUN apt-get clean