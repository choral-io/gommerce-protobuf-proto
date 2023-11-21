# Gommerce Protobuf Proto

Proto files of project `gommerce`.

```sh
# lint
buf lint --path gommerce

# format
buf format --path gommerce --diff --write

# generate
buf mod update
buf generate --path gommerce --template buf.gen.es.yaml
buf generate --path gommerce --template buf.gen.go.yaml
```
