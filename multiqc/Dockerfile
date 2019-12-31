FROM continuumio/miniconda:4.7.12

RUN conda install -c bioconda multiqc
RUN conda install -c bioconda fastqc=0.11.8
RUN conda install -c bioconda trimmomatic=0.39

RUN apt-get update && apt-get install -y procps
