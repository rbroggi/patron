FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o sqs-svc examples/sqs/main.go

ENTRYPOINT [ "/go/src/app/sqs-svc" ]
