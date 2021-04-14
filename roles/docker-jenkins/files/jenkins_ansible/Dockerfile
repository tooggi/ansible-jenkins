FROM jenkins/jenkins

USER root

RUN apt-get update && apt-get install python3 python3-distutils -y

RUN curl https://bootstrap.pypa.io/get-pip.py -o /tmp/get-pip.py && \
    python3 /tmp/get-pip.py && \
    python3 -m pip install ansible

USER jenkins