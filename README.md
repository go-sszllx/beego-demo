# beego-demo

## 使用beego生成工程框架
```
export GOPATH=/path/to/project/
bee new demo
```

## 创建go mod
```
cd demo
go mod init demo
```

## 构建
```
go build
```

## 根据Mysql中的表生成model文件
```
bee api hello -driver=mysql -conn="{username}:{password}@tcp(ip:port)/{schema}" -tables="{tablename}"
```
