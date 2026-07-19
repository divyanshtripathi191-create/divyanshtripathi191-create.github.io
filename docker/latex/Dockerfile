# docker/latex/Dockerfile
FROM ubuntu:22.04
ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
    ca-certificates curl wget gnupg lsb-release build-essential fontconfig fonts-dejavu \
    texlive-full latexmk poppler-utils ghostscript \
 && rm -rf /var/lib/apt/lists/*

WORKDIR /work
