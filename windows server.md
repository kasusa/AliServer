# 使用winscp
这个很方便的远程文件传输工具需要先在winserver上安装sshd服务端并开启之后才能使用。
[如何安装sshd和开启](https://blog.csdn.net/weixin_43064185/article/details/90080815)

1. 在 `设置-程序-添加功能` 里面下载sshd服务端
2. 开启代码
```
net start sshd
```
winscp的模式要选择`SFTP`

# IIS
先打开 **服务器管理器**
![image.png](http://ww1.sinaimg.cn/large/006rgJELly1gccfnkee9tj30s90en76n.jpg)

选择第二个 一路默认直到安装把相关iis的都勾选上就好。ASP的也勾上。

去阿里云安全组设置开启80端口即可。

# asp.net 部署
我是怎么部署的呢？

非常的诡异

我先用publish生成一堆本地文件，然后用winscp把他们都拷贝到webroot文件夹。

