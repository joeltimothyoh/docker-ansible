ARG IMAGE
FROM $IMAGE

RUN apt-get update \
    && apt-get install software-properties-common \
    && apt-add-repository --yes --update ppa:ansible/ansible \
    && apt-get install ansible \
    && rm -rf /var/lib/apt/lists/*

CMD [""]
ENTRYPOINT ["ansible"]