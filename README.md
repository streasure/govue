# govue
内部测试用

安装go1.13以上版本
设置环境变量
go env -w GOPROXY=https://goproxy.io,direct
go env -w GO111MODULE=on

下载go-zero
git clone https://github.com/tal-tech/go-zero
cd go-zero/tools/goctl
go build goctl.go

生成goctl.exe 复制到$gopath/bin下
goctl指令说明
自行浏览文档吧https://github.com/tal-tech/go-zero/blob/master/tools/goctl/goctl.md
