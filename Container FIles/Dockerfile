FROM python:3.9.2-alpine3.13
WORKDIR /home/upodder
RUN adduser -D upodder
RUN mkdir /home/upodder/output

RUN pip3 install upodder \
    && rm -rf /wheels \
    && rm -rf /root/.cache/pip/*

USER root