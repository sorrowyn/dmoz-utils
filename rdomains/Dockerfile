FROM alpine:3.8
MAINTAINER Carlos Lopes "cmplopes67@gmail.com"

RUN apk add --no-cache bash bash-doc bash-completion g++ musl-dev
RUN apk add --no-cache R
RUN apk add --no-cache R-dev

WORKDIR /app
CMD R --version
