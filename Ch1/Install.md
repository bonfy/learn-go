# 1. 安装 Go

这个主要还是看下 [官网](http://golang.org) 不过对国内用户还是有个Qiang的问题

国内的话，推荐[golangtc](http://www.golangtc.com/)，上面基本上该有的资源都有，算是个不错的镜像

安装主要分三种：

* Go源码安装：这是一种标准的软件安装方式。对于经常使用Unix类系统的用户，尤其对于开发者来说，从源码安装可以自己定制。
* Go标准包安装：Go提供了方便的安装包，支持Windows、Linux、Mac等系统。这种方式适合快速安装，可根据自己的系统位数下载好相应的安装包，一路next就可以轻松安装了。推荐这种方式
* 第三方工具安装：目前有很多方便的第三方软件包工具，例如Ubuntu的apt-get和wget、Mac的 Homebrew 等。这种安装方式适合那些熟悉相应系统的用户。

### Mac

Mac 用户推荐 Homebrew, 既快又方便，后期版本维护也简单

```
$ brew install go
```

### Windows

Windows 用户就推荐第二种方法了，也不用自己去处理一些可能发生的不必要的问题，选对 操作系统和 32位/64位就行

> Tips: Go的代理其实和设置 windows cmd的代理一样的
> 代理的使用环境一般为
> * Golang.org 访问不了
> * 公司内网

```cmd
set HTTP_PROXY=http://user:password@proxy:port
set HTTPS_PROXY=https://user:password@proxy:port
```
