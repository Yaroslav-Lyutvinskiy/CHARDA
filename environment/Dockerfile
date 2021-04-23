# hash:sha256:49392ee53198359be91cac2e16606390c4dee673da28a3d5d6c309c54e38e822
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
    configobj==5.0.6 \
    isospecpy==2.1.4 \
    jdc==0.0.9 \
    pyopenms==2.6.0
