FROM node:10.16

RUN apt-get update && apt-get install -y python-dev  && \
  wget https://bootstrap.pypa.io/get-pip.py && \
  python get-pip.py && \
  rm get-pip.py && \
  pip install awscli && \
  mkdir /app

WORKDIR /app
