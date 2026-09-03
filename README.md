# hello_world

A tiny Go Hello World used as a POC for Murdok.

## Clone

```shell
git clone https://github.com/murdok-ekhart/hello_world.git
cd hello_world
```

To work on the Hello World code, check out the `development` branch:

```shell
git checkout development
```

## Install

Requires [Go](https://go.dev/dl/) 1.22+.

From the repo root (on `development`):

```shell
go install .
```

That puts the `hello_world` binary on your `GOBIN` / `GOPATH/bin`. Make sure that directory is on your `PATH`.

You can also build a local binary without installing:

```shell
go build -o hello_world .
```

## Run

After `go install`:

```shell
hello_world
```

Or without installing:

```shell
go run .
```

Or with the built binary:

```shell
./hello_world
```

Expected output:

```text
Hello, World
```
