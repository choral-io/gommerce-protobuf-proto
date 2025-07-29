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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Third-party Code

This repository includes code from third-party sources with different licenses:

-   **Google RPC Types** (`google/rpc/` directory): Contains protocol buffer types from the [googleapis](https://github.com/googleapis/googleapis) project, licensed under the Apache-2.0 License. Copyright belongs to Google LLC. These types are used to ensure compatibility with gRPC and ConnectRPC implementations.

For detailed third-party license information, see [THIRD_PARTY_LICENSES](THIRD_PARTY_LICENSES).
