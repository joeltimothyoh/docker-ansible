ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk update \
    && apk search ansible \
    && apk add --no-cache ansible=7.5.0-r0 openssh-client \
    && rm -rf /var/cache/apk/*

CMD ["/bin/sh"]
