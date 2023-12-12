### decrypt

* command inspire by [github.com/gorilla/websocket/tree/main/examples/command](https://github.com/gorilla/websocket/tree/main/examples/command)
* crypt inspire by [github.com/panshiqu/crypt](https://github.com/panshiqu/crypt)

```bash
echo hello world | go run crypt.go -s 5277888888 > 111111
cat 111111
go run crypt.go -r -s 5277888888 < 111111
```

```bash
go build crypt.go
go run command.go bash
date "+%Y-%m-%d %H:%M"
md5 -s "DATE.TOKEN"
```

Visit `http://localhost:8080?c=md5`

Send `crypt 5277 888888`
