FROM alpine:3.14.3

RUN apk add --update bash socat && rm -rf /var/cache/apk/*
ADD ./run.sh /

entrypoint ["/run.sh"]
