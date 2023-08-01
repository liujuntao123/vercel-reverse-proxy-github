# vercel-reverse-proxy-github

本项目是基于vercel反向代理的github专用免翻代理。完全免费。

github页面访问，资源下载均适用。

vercel现在每月有100GB的免费流量。个人使用应该完全足够。

## 部署
[![Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/liujuntao123/vercel-reverse-proxy-github)


## 使用方法
1 部署。部署有两种方法，一是直接点击上方按钮一键部署，二是可以先fork本项目，再登录[vercel](https://vercel.com/)网站新建。vercel可以通过github一键注册只需要绑定手机号支持cn
![新建项目](img/newproject.png)

2 绑定自己的域名(不是必须，使用vercel自带的子域名也可以，但是自带的域名vercel.app在国内网络环境不好的情况下不可用) 可以自行申请一个域名，阿里云腾讯云啥的，一年也就10来块钱。
绑定域名时按照vercel上的说明配置即可，其实就是在你的域名上配了一个子域名，cname到vercel服务器


## 示例
比如原地址为 https://github.com/liujuntao123/vercel-reverse-proxy-github，把其中`github.com`替换为自己vercel服务域名即可。
比如我的vercel服务域名为`vercel-reverse-proxy-github.vercel.app`,那么就访问https://vercel-reverse-proxy-github.vercel.app/liujuntao123/vercel-reverse-proxy-github

