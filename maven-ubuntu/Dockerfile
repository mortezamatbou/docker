FROM ubuntu:latest AS builder

# RUN tar -xvf apache-maven-3.9.5-bin.tar.gz
ADD apache-maven-3.9.5-bin.tar.gz /opt/

ENV M2_HOME="/opt/apache-maven-3.9.5"
ENV PATH="$M2_HOME/bin:$PATH"
RUN export PATH

WORKDIR /scripts