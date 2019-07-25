FROM ubuntu:18.10

MAINTAINER Paul White

USER root

WORKDIR /root

RUN apt-get update

# Install vim editor and netstat cmd
RUN apt-get install vim -y
RUN apt-get install net-tools -y

RUN apt update
RUN apt install software-properties-common -y
RUN add-apt-repository ppa:ubuntu-toolchain-r/ppa
RUN apt update
RUN apt install python3.7 -y
RUN apt install python3-pip -y
RUN apt-get install curl -y
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python3.7 get-pip.py
