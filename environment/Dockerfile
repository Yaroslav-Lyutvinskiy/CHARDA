# hash:sha256:c32b9772cbc99e6217b01eb7307d5f1690ea90ad37c280608c0eadfb3b8b17b1
FROM registry.codeocean.com/codeocean/miniconda3:4.8.2-python3.8-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        h5py==2.10.0 \
        jupyterlab==3.0.11 \
        matplotlib==3.3.4 \
        numpy==1.19.2 \
        pandas==1.2.4 \
        scikit-learn==0.24.1 \
        scipy==1.6.2 \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    isospecpy==2.1.4 \
    pyopenms==2.6.0
