# Hypi's public gRPC models

* [MekaDB](mekadb_client.proto)
  * Higher level clients are available in some languages
    * [Rust](https://crates.io/crates/mekadb)
    * [Java](https://central.sonatype.com/artifact/app.hypi.mekadb/client)
    * [Python](https://pypi.org/project/mekadb/)
    * [NodeJS](https://www.npmjs.com/package/@hypi/mekadb)

## MekaDB

Hypi's high performance, distributed SQL database.
You can copy the gRPC file into your project manually or you can add a git dependency to this repo.

For example at the root level of your project, you can
```shell
git submodule add git@github.com:hypi-universe/public-grpc-models.git path/in/your/project
```
Depending on your language, generate only the client.
