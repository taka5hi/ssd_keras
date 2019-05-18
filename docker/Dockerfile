FROM tensorflow/tensorflow:nightly-gpu-py3-jupyter

WORKDIR /tf
COPY ./requirements.txt ./
RUN apt-get install libsm6 libxrender1 libxext6 -y
RUN pip install -r requirements.txt
