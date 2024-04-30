# frp

根据[xz师傅二开的frp](https://github.com/X1r0z/frp)再次进行了二开 添加了一个小功能

可以命令行一键执行frpc  并且是加密的密文



## 使用

![image-20240430221328649](https://nuthecz.oss-cn-hangzhou.aliyuncs.com/file/202404302230237.png
)

![image-20240430221450454](https://nuthecz.oss-cn-hangzhou.aliyuncs.com/file/202404302230321.png)

key和iv值根据自己的需求来进行修改  然后输入值的话按照`ip:port:Socks_Port`的格式输入  (记得改源码重新编译)



```
frpc.exe -s 密文
```

![image-20240430222036614](https://nuthecz.oss-cn-hangzhou.aliyuncs.com/file/202404302230748.png)



然后frps.exe就会生成随机的socks账号密码

![image-20240430222152068](https://nuthecz.oss-cn-hangzhou.aliyuncs.com/file/202404302230300.png)



后续的流量特征修改 写好了再更新