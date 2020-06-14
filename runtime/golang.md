# Golang

### 生命周期
Golang 的生命周期策略为，支持最新的2个大版本。例如，Go 1.5在Go 1.7发布之前一直受支持，Go 1.6在Go 1.8发布之前一直受支持。

### 兼容性
Golang 1.x 版本保持向下兼容，因此任何低版本的 Go 语言程序都可以直接通过新版本直接编译来提升性能和修复 bug。

但如果引入了 cgo 则可能要考虑 gcc 的兼容性，在此常见下应该单独考虑。

Golang 兼容性指 Go 语言本身，并不包括 Go 相关工具的兼容性。在某些版本中部分 go 相关工具可能存在兼容性破坏，例如 go get

### Golang 版本
以下简要列出最近的若干版本，完整的 release 参照 [Go Release](https://golang.org/doc/devel/release.html)

|版本|发布日期|支持状态|
|--|--|--|
|Go1.14|2020/02/25|支持|
|Go1.13|2019/09/03|支持|
|Go1.12|2019/02/25|不支持|
|Go1.11|2018/08/24|不支持|
|Go1.10|2018/02/16|不支持|