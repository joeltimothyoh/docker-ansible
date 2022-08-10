ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk search ansible \
    && apk add --no-cache ansible=6.2.0-r0 openssh-client

CMD ["/bin/sh"]
