# hash:sha256:48107899d4fe4e6e84b56e4d41c163faa64087fa99be07564ea781bc6c4480f8
FROM registry.codeocean.com/codeocean/miniconda3:4.8.2-python3.8-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        h5py \
        matplotlib \
        numpy \
        pandas \
        scipy \
        sklearn \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    isospecpy \
    pyopenms
