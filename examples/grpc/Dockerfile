FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o grpc-svc examples/grpc/main.go

ENTRYPOINT [ "/go/src/app/grpc-svc" ]
