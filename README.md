# sandbox-nginx-limit-req

Sandbox for nginx `ngx_http_limit_req_module` module

## Usage

```sh
$ docker-compose up

$ curl http://localhost:8080
Hello, backend!

$ curl http://localhost:8081
Hello, backend!

$ curl http://localhost:8082
Hello, backend!
```
