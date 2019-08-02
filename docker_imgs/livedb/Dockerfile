FROM ubuntu:18.10

MAINTAINER Paul White

USER root

WORKDIR /root

RUN apt-get update

# Install vim editor and netstat cmd
RUN apt-get install vim -y
RUN apt-get install net-tools -y

RUN apt install mysql-server -y
#CMD ["find", "/var/lib/mysql -type f -exec touch {} \;"]
