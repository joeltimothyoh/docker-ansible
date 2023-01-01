ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk update \
    && apk search ansible \
    && apk add --no-cache ansible=2.10.7-r0 openssh-client \
    && rm -rf /var/cache/apk/*

CMD ["ansible"]
