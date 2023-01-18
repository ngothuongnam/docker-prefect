FROM ubuntu:22.04
RUN apt update -y \
    && apt upgrade -y \
    && apt install python3-pip -y \
    && apt-get install libsasl2-dev -y \
    && pip install --upgrade pip setuptools wheel \
    && pip install -U prefect
