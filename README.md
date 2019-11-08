AliServer

我还得重新搞一份……FML

我简直要哭死啦……
好不容易写的东西都没有了……

> 下次push完毕一定要去看看有没有成功的push

# 软件
* [winscp](https://winscp.net/eng/index.php) （文件传输）


# 教程
* [在阿里云上安装MySQL并配置远程连接](https://blog.csdn.net/ldx19980108/article/details/80343904)
* nigix.conf
`/etc/nginx`
```conf
events { }
http {
 server {
     charset utf-8;
     location / {
         #这里是网页的根目录
         root /Mysite; 
     }
 }      
}
```

放完网页之后要给所有的网页文件chmod 777权限。