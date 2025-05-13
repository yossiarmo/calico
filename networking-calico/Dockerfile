FROM quay.io/coreos/etcd:v3.4.20 as etcd

FROM python:3.12.10

COPY --from=etcd /usr/local/bin/etcd /usr/local/bin/etcd

RUN pip3 install tox==3.25.1
