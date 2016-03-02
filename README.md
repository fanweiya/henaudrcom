# henau-drcom

[![Join the chat at https://gitter.im/fanweiya/henaudrcom](https://badges.gitter.im/fanweiya/henaudrcom.svg)](https://gitter.im/fanweiya/henaudrcom?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


**heau-drcom**是一款专为henau打造的openwrt编译版本，内置henau-drcom认证,简单几步可实现henau校园网自动认证。
 
- **drcom认证** ：实现一号多用，节省每月网费；
- **科学上网** ：内置shadowsockes,redsockes2,ChinaDNS实现科学上网；
- **其他功能** ：支持aria2和迅雷远程下载，USB 打印服务器和MJPG-streamer等。

-------------------
## 路由器

>**newifi mini**

### 刷机

>newifi mini如何刷openwrt可以参考这个
>http://jingyan.baidu.com/article/647f0115b3d5897f2148a83e.html

### 配置drcom

>使用**WinSCP**连接路由进入`/usr/bin/drcom.py`填入自己的上网账号,密码保存。

### 配置科学上网

>不做祥述，有兴趣的同学可以自行完成配置。

####Example image

![eg1](https://raw.githubusercontent.com/iamfanweiya/henau-drcom/master/eg1.jpg)
![eg2](https://raw.githubusercontent.com/iamfanweiya/henau-drcom/master/eg2.jpg)
![eg3](https://raw.githubusercontent.com/iamfanweiya/henau-drcom/master/eg3.jpg)

## 感谢

>[drcom-generic](https://github.com/drcoms/drcom-generic)，openwrt，shadowsockes,redsockes2,ChinaDNS等项目

## 反馈与建议

- 博客：[BLOG](http://fanweiya.cn)

## 许可证

AGPLv3
特别指出禁止任何个人或者公司将代码投入商业使用，由此造成的后果和法律责任均与本人无关。
