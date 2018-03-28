FROM golang:1.10.0-alpine3.7
MAINTAINER Michael Hausenblas <michael.hausenblas@gmail.com>
RUN go get github.com/fullstorydev/grpcurl && \
    go install github.com/fullstorydev/grpcurl/cmd/grpcurl
USER nobody:nobody
