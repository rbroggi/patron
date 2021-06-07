FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o http-sec-svc examples/http-sec/main.go

ENTRYPOINT [ "/go/src/app/http-sec-svc" ]
