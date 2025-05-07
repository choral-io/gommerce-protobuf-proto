# Gommerce Protobuf Proto

Proto files of project `gommerce`.

```sh
# update
buf dep update

# lint
buf lint --path gommerce

# format
buf format --path gommerce --diff --write

# generate
buf generate --template buf.gen.es.yaml --path gommerce --path google
buf generate --template buf.gen.go.yaml --path gommerce

# publish
buf build
buf push --label $(git rev-parse --abbrev-ref HEAD)
```
