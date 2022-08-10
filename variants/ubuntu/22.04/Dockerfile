ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-cache policy ansible \
    && apt-get install -y ansible=2.10.7+merged+base+2.10.8+dfsg-1 openssh-client \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
