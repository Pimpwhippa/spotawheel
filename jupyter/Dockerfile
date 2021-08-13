FROM jupyter/pyspark-notebook:latest
WORKDIR /jupyter
ADD . /jupyter
RUN pip install -r requirements.txt
ENV TERM xterm