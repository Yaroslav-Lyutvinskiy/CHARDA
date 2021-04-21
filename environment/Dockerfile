# hash:sha256:c18ce069c5bdfefa2a4c042a63a12c58e738fc373874a66855940235e10972ed
FROM registry.codeocean.com/codeocean/miniconda3:4.8.2-python3.8-ubuntu18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        h5py==2.10.0 \
        jupyter==1.0.0 \
        jupyterlab==3.0.11 \
        matplotlib==3.3.4 \
        numpy==1.19.2 \
        pandas==1.2.4 \
        scikit-learn==0.24.1 \
        scipy==1.6.2 \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    configobj \
    isospecpy==2.1.4 \
    pyopenms==2.6.0
