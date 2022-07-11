# Interpreter in Go

## GitHooks の設定

```sh
$ chmod -R u+x githooks
$ git config --local core.hooksPath githooks/pre-commit
```

## 環境構築 in Docker

```sh
$ docker run --rm -t -i --entrypoint="" -v $(pwd):/go/src/monkey golang:1 <command>
```

`<command>` には， `go test` や `bash` などを入れます．
