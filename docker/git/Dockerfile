FROM alpine:3.5

MAINTAINER Tiago Alves

RUN apk --update add git openssh && \
    rm -rf /var/lib/apt/lists/* && \
    rm /var/cache/apk/*

VOLUME /git
WORKDIR /git

CMD ["git","--help"]
