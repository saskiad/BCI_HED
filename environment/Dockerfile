# hash:sha256:f3b0af707b3d8939158985a638d3fb931fb8b59aee63590b1e2ab3a452f4bf3c
ARG REGISTRY_HOST
FROM $REGISTRY_HOST/codeocean/mambaforge3:23.1.0-4-python3.10.12-ubuntu22.04

ARG DEBIAN_FRONTEND=noninteractive
ARG GIT_ASKPASS
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    aind-data-access-api==1.4.0 \
    hdmf==3.14.6 \
    hdmf-zarr==0.11.3 \
    matplotlib==3.10.5 \
    numpy==2.2.6 \
    nwbwidgets==0.11.3 \
    pandas==2.3.2 \
    pynwb==3.0.0
