FROM golang:alpine

LABEL maintainer="whiran"

RUN mkdir /go/src/app

WORKDIR /go/src/app

ADD . .

RUN ls

RUN go mod init

RUN go build  -o helloworld

EXPOSE 6111

CMD ["./helloworld"]