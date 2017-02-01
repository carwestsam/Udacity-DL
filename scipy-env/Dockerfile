FROM ubuntu:16.04
RUN rm /bin/sh && ln -s /bin/bash /bin/sh
RUN apt-get update
RUN apt-get install -y wget zip bzip2

RUN wget -O /tmp/miniconda2.sh https://repo.continuum.io/miniconda/Miniconda2-latest-Linux-x86_64.sh
RUN /bin/bash /tmp/miniconda2.sh -b -p /opt/miniconda2
ENV PATH="/opt/miniconda2/bin:${PATH}"




