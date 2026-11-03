```shell
go mod tidy
$env:CGO_ENABLED="0"; $env:GOOS="windows"; $env:GOARCH="amd64"
go build -o server.exe .
.\server.exe
```