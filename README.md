# gRPC proto for other services

- https://github.com/grpc-ecosystem/grpc-gateway

```shell
go install github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-grpc-gateway@latest
go install github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-openapiv2@latest

make build-gateway
make protoc-go
make protoc-go-gateway
make protoc-openapiv2-gateway
```
