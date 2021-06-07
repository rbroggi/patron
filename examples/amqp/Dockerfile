FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o amqp-svc examples/amqp/main.go

ENTRYPOINT [ "/go/src/app/amqp-svc" ]
