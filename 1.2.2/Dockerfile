FROM golang:1.2.2

RUN go get github.com/mitchellh/gox
RUN gox -build-toolchain

CMD go get -d ./... && gox
