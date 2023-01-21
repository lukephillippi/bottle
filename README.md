# bottle

[![Tests](https://github.com/lukephillippi/bottle/actions/workflows/tests.yaml/badge.svg)](https://github.com/lukephillippi/bottle/actions/workflows/tests.yaml) [![Go Reference](https://pkg.go.dev/badge/go.luke.ph/bottle.svg)](https://pkg.go.dev/go.luke.ph/bottle)

A Go package used to test the Go vanity URL server, [go.luke.ph](https://go.luke.ph).

This package enforces a [canonical import path](https://go.dev/doc/go1.4#canonicalimports); the following command should succeed:

```shell
go get -u go.luke.ph/bottle
```

The following command should **not** succeed:

```shell
go get -u github.com/lukephillippi/bottle
```

## Licensing

[The Unlicense](./LICENSE.md)
