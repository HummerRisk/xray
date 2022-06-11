FROM ubuntu:latest

WORKDIR /opt

RUN apt-get update -y && apt-get install -y unzip wget

RUN wget https://github.com/chaitin/xray/releases/latest/download/xray_linux_amd64.zip -O /opt/xray_linux_amd64.zip \
     && cd /opt && unzip xray_linux_amd64.zip \
     && mkdir -p /opt/hummerrisk/xray \
     && cp -rp /opt/xray_linux_amd64 /opt/hummerrisk/xray

