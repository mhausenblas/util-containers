FROM golang:1.10.0-alpine3.7
MAINTAINER Michael Hausenblas <michael.hausenblas@gmail.com>
RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh && \
    go get github.com/fullstorydev/grpcurl && \
    go install github.com/fullstorydev/grpcurl/cmd/grpcurl
USER nobody:nobody
