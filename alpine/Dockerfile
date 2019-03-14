ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk update \
    && apk add --no-cache ansible \
    && rm -rf /var/cache/apk/* \
    && rm -rf /tmp/*

CMD ["/bin/sh"]