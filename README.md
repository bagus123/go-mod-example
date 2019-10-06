#go-mod-example


#installation

```shell

#clone repository
git clone https://github.com/bagus123/go-mod-example.git

#download dependencies
go build

```


#list command of go mod

```shell
#init module
go mod init github.com/[username]/[repo_name]

#download dependencies
go build

#remove unnecessary/unused module
go mod tidy

#make folder vendor (list of module dependencies)
go mod vendor
```




