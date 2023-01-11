# gRPC concept and its technical
## 1. Overview
### 1.1 Introduction
- gRPC - General-purpose Remote Procedure Call
- Free Framework developed by Google
- A partition of Cloud Native Computing Foundation such as Docker, Kubernetes
- Built on HTTP/2.0
### 1.2 Functions
- Definition message (data, request, response) and service (service name, rpc endpoint) using Protocol Buffer
- Generate multi language code by file .proto
### 1.3 Compare with REST
| rGPC        | REST |
| ----------- | ----------- |
| Protocol Buffer, binary base, small, lightweight, fast      | JSON, text base, bigger, slower       |
| HTTP/2.0 - 2015   | HTTP/1.0 - 1997        |
| Bidirection & async  | Client --> Server request |
| Stream support   | request, response        |
| API Oriented   | CRUD Oriented (POST, GET, PUT, DELETE)        |
