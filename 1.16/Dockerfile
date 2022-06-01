FROM golang:1.16.15-alpine3.15

ARG CREATED
ARG REVISION
ARG TITLE
ARG VERSION

# MetaData
LABEL org.opencontainers.image.vendor="Elastic Path Software Inc."
LABEL org.opencontainers.image.source="https://gitlab.elasticpath.com/internal/docker-go"
LABEL org.opencontainers.image.title=$TITLE
LABEL org.opencontainers.image.description="Docker image based on Alpine Linux distribution (http://alpinelinux.org/). This is the base docker image to be used for all services written in go."
LABEL org.opencontainers.image.created=$CREATED
LABEL org.opencontainers.image.version=$VERSION
LABEL org.opencontainers.image.revision=$REVISION

RUN apk -U upgrade