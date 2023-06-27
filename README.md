
## 测试 go install 如何引用github的版本





``` bash
# 运行如下命令进行测试
# go mod init github.com/hfbhfb/go-version-test
# go mod tidy
# git tag 0.1 <commit_hash>
# git push origin 0.1

go install github.com/hfbhfb/go-version-test@0.1
go-version-test
go install github.com/hfbhfb/go-version-test@0.2
go-version-test

```




