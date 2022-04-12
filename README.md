# Interpreter in Go


## 環境構築 in Docker

```sh
$ docker run --rm -t -i --entrypoint="" -v $(pwd):/go/src/monkey golang:1.18 <command>
```

`<command>` には， `go test` や `bash` などを入れます．
