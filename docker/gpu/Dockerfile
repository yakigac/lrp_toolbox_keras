FROM tensorflow/tensorflow:1.7.0-gpu
LABEL maintainer="Ryohei Kuroki <ryohei.kuroki@gmail.com>"

RUN apt-get update && apt-get upgrade -qqy
RUN pip install -q keras

COPY jupyter_notebook_config.py /root/.jupyter/
