# Woodpecker

Woodpecker (啄木鸟) 是一个系统信息获取工具


CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build
CGO_ENABLED=0 GOOS=darwin GOARCH=amd64 go build
CGO_ENABLED=0 GOOS=windows GOARCH=amd64 go build


提供一键获取系统信息

以及获取单个指标项信息，针对单指标项目持续输出


## 初衷

比较直观的看到自己想看到的参数信息，而不是通过Linux系统获取 /proc/ 的信息去查看，省去一部分计算的时间