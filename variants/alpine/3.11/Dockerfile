ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk search ansible \
    && apk add --no-cache ansible=2.9.18-r0 openssh-client

CMD ["/bin/sh"]
