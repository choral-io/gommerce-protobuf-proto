# Gommerce Protobuf Proto

Proto files of project `gommerce`.

```sh
# lint
buf lint --path gommerce

# format
buf format --path gommerce --diff --write

# generate
buf mod update
buf generate --template buf.gen.es.yaml --path gommerce --path google
buf generate --template buf.gen.go.yaml --path gommerce
```
