FROM jupyter/tensorflow-notebook

USER root
RUN rm /bin/sh && ln -s /bin/bash /bin/sh
RUN apt-get update && apt-get install -y wget zip

USER $NB_USER

RUN wget -O /home/jovyan/fast-style-transfer.zip https://github.com/lengstrom/fast-style-transfer/archive/master.zip && unzip /home/jovyan/fast-style-transfer.zip && rm /home/jovyan/fast-style-transfer.zip



