# CURL

## GET

```bash
curl 0.0.0.0:8080/v1/sources/9
```

## GET with response status

```bash
curl -v 0.0.0.0:8080/v1/sources/9
```

## POST

```bash
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"username":"xyz","password":"xyz"}' \
  http://0.0.0.0:3000/kv
```
