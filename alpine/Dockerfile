ARG IMAGE
FROM $IMAGE

RUN apk update \
    && apk add --no-cache ansible \
    && rm -rf /var/cache/apk/* \
    && rm -rf /tmp/*

CMD [""]
ENTRYPOINT ["ansible"]