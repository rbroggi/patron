FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o kafka-svc examples/kafka/main.go

ENTRYPOINT [ "/go/src/app/kafka-svc" ]
