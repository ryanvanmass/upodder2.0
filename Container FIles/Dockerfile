FROM python:3.9.2-alpine3.13
WORKDIR /root

RUN pip3 install upodder \
    && rm -rf /wheels \
    && rm -rf /root/.cache/pip/*

USER root