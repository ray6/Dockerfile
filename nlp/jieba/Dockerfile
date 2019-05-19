FROM ubuntu:16.04
MAINTAINER RayLiu
WORKDIR /root

RUN apt-get update && apt-get -y upgrade && apt-get -y install vim && apt-get -y install python3-pip && echo 'alias python="python3"' >> ~/.bashrc && echo 'alias pip="pip3"' >> ~/.bashrc
RUN pip3 install --upgrade pip && python3 -m pip install jieba \
												jupyterlab \
												numpy \
												networkx
