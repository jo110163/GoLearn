# README

第一步，通过 go mod init 创建 go.mod 文件，将当前项目变为一个 Go Module
    go mod init github.com/bigwhite/module-mode
第二步，通过 go mod tidy 命令自动更新当前 module 的依赖信息；
    go mod tidy
第三步，执行 go build，执行新 module 的构建。
    go build