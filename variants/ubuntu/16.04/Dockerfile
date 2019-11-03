ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-get install -y ansible=2.0.0.2-2ubuntu1.3 openssh-client \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
