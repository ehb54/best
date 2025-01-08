FROM debian:latest

ARG DEBIAN_FRONTEND=noninteractive
ENV PATH="/best/bin:$PATH"
RUN apt-get update
RUN apt-get install -y git
RUN git clone https://github.com/ehb54/best
WORKDIR /work
