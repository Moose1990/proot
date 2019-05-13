FROM alpine:3.9.4

RUN apk update && apk add \
        bsd-compat-headers \
        libarchive-dev \
        linux-headers \
        talloc-dev

WORKDIR /usr/src/proot
COPY . /usr/src/proot
