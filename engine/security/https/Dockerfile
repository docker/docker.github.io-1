FROM debian:latest@sha256:e538a2f0566efc44db21503277c7312a142f4d0dedc5d2886932b92626104bff

RUN apt-get update && apt-get install -yq openssl

ADD make_certs.sh /


WORKDIR /data
VOLUME ["/data"]
CMD /make_certs.sh
