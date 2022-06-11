FROM ubuntu:latest

RUN apt-get update && apt-get install wget && wget https://github.com/chaitin/xray/releases/latest/download/xray_linux_amd64.zip

RUN unzip xray_linux_amd64.zip

COPY ./xray_linux_amd64 /opt/hummerrisk/xray/
