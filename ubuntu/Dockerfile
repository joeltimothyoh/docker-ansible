ARG IMAGE
FROM $IMAGE

RUN apt-get update \
    && apt-get install -y software-properties-common \
    && apt-add-repository --yes --update ppa:ansible/ansible \
    && apt-get install -y ansible \
    && rm -rf /var/lib/apt/lists/* \
    && rm -rf /tmp/*

CMD ["/bin/bash"]