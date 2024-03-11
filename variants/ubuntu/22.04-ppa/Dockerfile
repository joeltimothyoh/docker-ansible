ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-get install -y software-properties-common \
    && apt-add-repository --yes --update ppa:ansible/ansible \
    && apt-cache policy ansible \
    && apt-get install -y ansible=9.3.0-1ppa~jammy openssh-client \
    && apt-get remove -y --autoremove software-properties-common \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
