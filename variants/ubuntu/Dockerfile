ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-get install -y ansible openssh-client \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
