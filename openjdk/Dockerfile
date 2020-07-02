FROM ubuntu:16.04
RUN sed -i 's/ports.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list && \
    apt-get update && \
    apt-get install openjdk-8-jdk -y && \
    rm -rf /var/lib/apt/lists/*
