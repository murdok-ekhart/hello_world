# hello_world

A tiny Go program that logs a hello with [zerolog](https://github.com/rs/zerolog).

## Clone

```shell
git clone https://github.com/murdok-ekhart/hello_world.git
cd hello_world
```

## Install

Needs [Go](https://go.dev/dl/) 1.23 or newer (that's zerolog's current floor).

From the repo root:

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

It writes an info line to stderr via zerolog's console writer, for example:

```text
10:49PM INF the coffee's on, the compiler's warm, hello from this side of the glass
```
