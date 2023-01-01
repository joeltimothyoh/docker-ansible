ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-cache policy ansible \
    && apt-get install -y ansible=2.5.1+dfsg-1ubuntu0.1 openssh-client \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
