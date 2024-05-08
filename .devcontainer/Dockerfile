# MINSIGSTKSZ usage requires <2.34
FROM --platform=amd64 ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
RUN echo 'debconf debconf/frontend select Noninteractive' | debconf-set-selections
RUN apt update && apt upgrade -y
RUN apt install -y gcc g++ clang make gdb valgrind graphviz imagemagick git zip unzip
