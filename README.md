# grpc-echo-service

A simple RPC example implemented using gRPC

## Instalation

Setup [learnscalability/vm](https://github.com/learnscalability/vm)

Install project dependencies
```sh
$ cd ~/go/src/github.com/learnscalability/grpc-echo-service
$ glide install
```

## How to run

Make sure the protobuf generated `pb` package is up-to-date:
```
$ ./script/proto
```

Running the server
```
go run ./cmd/server/main.go -bind="0.0.0.0:3000"
```
