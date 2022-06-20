FROM golang:1.19beta1

COPY . /go/src/app
WORKDIR /go/src/app
RUN go get -d -v
RUN go install -v

EXPOSE 80

ENTRYPOINT ["app"]