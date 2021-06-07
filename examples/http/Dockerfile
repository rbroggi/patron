FROM golang:1.14

WORKDIR /go/src/app
COPY . .

RUN go build -o http-svc examples/http/main.go
EXPOSE 50000

ENTRYPOINT [ "/go/src/app/http-svc" ]
