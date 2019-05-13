FROM alpine:3.9.4

RUN apk update && apk add \
        bsd-compat-headers \
        coreutils \
        gdb \
        libarchive-dev \
        linux-headers \
        strace \
        swig \
        talloc-dev

WORKDIR /usr/src/proot
COPY . /usr/src/proot
