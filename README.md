# traefik-plugin-panic
Reproduce the panic in local plugin mode

```
$ docker compose up
$ curl 'http://localhost:8080/drip?numbytes=5&duration=5&code=200' -H 'Host: httpbin'
# abort the request
# see panic in traefik logs
```
