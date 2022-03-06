FROM ubuntu:18.04

WORKDIR /usr/src/app
ENV PATH="/root/miniconda3/bin:${PATH}"
ARG PATH="/root/miniconda3/bin:${PATH}"
RUN apt-get update

RUN apt-get install -y wget && rm -rf /var/lib/apt/lists/*

RUN wget \
    https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh \
    && mkdir /root/.conda \
    && bash Miniconda3-latest-Linux-x86_64.sh -b \
    && rm -f Miniconda3-latest-Linux-x86_64.sh 
COPY environment.yaml ./
RUN conda install --name base jupyter nb_conda_kernels
RUN conda env create -f environment.yaml
ENTRYPOINT [ "jupyter", "notebook", "--ip", "0.0.0.0", "--no-browser", "--allow-root"]