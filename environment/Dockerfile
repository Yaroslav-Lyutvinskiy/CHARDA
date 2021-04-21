# hash:sha256:65ca064b047d3668b95a158f48ad5fc4c081ae0811df976863098168372b91d6
FROM registry.codeocean.com/codeocean/miniconda3:4.8.2-python3.8-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        h5py \
        matplotlib \
        numpy \
        pandas \
        scipy \
        sklearn \
    && rm -rf /var/lib/apt/lists/*
