#### 郝大在GoHacker微信社群提出的问题：



---



##### 1.GoPath中的第一个ws和第二个，第三个ws有什么区别？

* bin	编译后生成的可执行文件
* pkg  编译文件（比如：.a）
* src   源代码

##### 2.ws和GOPATH有啥区别，分别怎么设置？

ws(workspace)即工作空间，包含bin,pkg,src，在GOPATH目录下。

##### 3.GOBIN是什么？起到什么作用？

GOBIN即go install编译存放路径。不允许设置多个路径。可以为空。为空时则遵循“约定优于配置”原则，可执行文件放在各自GOPATH目录的bin文件夹中。

##### 4.slice append的问题，怎么高效删除其中的元素？要注意哪些问题？

```go
append(s[:i], s[i+1:]...)
```



##### 5.切片值在append时会发生什么？[]byte和string的值互相转换时会发生什么？

##### 6.Go写的命令怎么接收参数？

##### 7.你们用过syscall包的哪些常量？它们都代表什么？

##### 8.FileMode都有哪些？都代表什么？

