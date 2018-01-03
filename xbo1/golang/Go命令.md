---
title: "Go命令"
date: 2018-01-03T10:35:40+08:00
draft: true

featuredImage: ""
categories: [golang]
tags: [学习]
author: ""
---

#### Go工作区
在 Mac 或 Linux 操作系统下，Go 工作区应该设置在 ```$HOME/go``` 。所以我们要在 ```$HOME``` 目录下创建 go 目录。

而在 Windows 下，工作区应该设置在 C:\Users\YourName\go。所以请将 go 目录放置在 C:\Users\YourName。

也可以通过设置 GOPATH 环境变量，用其他目录来作为工作区


#### 命令
```
go run 
go build
go install 

```

#### Hello world
```
package main

import "fmt"

func main() {
	fmt.Println("hello world")
}
```