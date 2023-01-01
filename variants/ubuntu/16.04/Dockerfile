ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-cache policy ansible \
    && apt-get install -y ansible=2.1.1.0-1~ubuntu16.04.1 openssh-client \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
