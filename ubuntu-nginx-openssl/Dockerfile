FROM ubuntu:16.04

RUN apt-get update && apt-get install git make gcc -y \
	&& git clone https://github.com/openssl/openssl.git \
    && cd openssl && ./config \
    && make install
