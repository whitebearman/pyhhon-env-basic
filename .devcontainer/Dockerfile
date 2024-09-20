FROM python:3.10

USER root

RUN apt-get update && \
    apt-get -y install --no-install-recommends \
    apt-utils \
    git \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*

RUN pip install --upgrade pip
