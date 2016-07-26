## Github简介

---

确切的说 GitHub 是一家公司，位于旧金山，由 Chris Wanstrath, PJ Hyett 与 Tom Preston-Werner 三位开发者在2008年4月创办。这是它的 Logo：

![img](http://mmbiz.qpic.cn/mmbiz/159icnNTXChOuyQpicC2gcdvl7XDJIuTHmKVibtPjZ6cKgMGx2MQe0149bLpDImGDVcOP9IWUF6IFBPstCnBN3Shg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1)

2008年4月10日，GitHub正式成立，地址：https://github.com/ ，主要提供基于git的版本托管服务。一经上线，它的发展速度惊为天人，截止目前，GitHub 已经发展成全球最大的开（同）源（性）社区。很多人以为 GitHub 就是 Git，其实这是一个理解误区。 GitHub 主要提供基于 git 的版本托管服务。也就是说现在 GitHub 上托管的所有项目代码都是基于 Git 来进行版本控制的，所以 Git 只是 GitHub 上用来管理项目的一个工具而已，GitHub 的功能可远不止于此！

## 加入Gayhub

---

进入官网[https://github.com/] 按平常一样注册个账号（ps:昵称取好听点的，不然以后后悔）

gayhub主页（可能新用户什么都没有，只有工具栏。。。）

![](http://ww3.sinaimg.cn/large/6bf00bd8gw1f67bb8edsuj20yp0kigsm.jpg)

- 导航栏，从左到右依次是 GitHub 主页按钮、搜索框、PR、Issues、Gist、消息提醒、创建项目按钮、我的账号相关。


- 我的时间线，就是你关注的一些人的活动会出现在这里，比如如果你们关注我了，那么以后我 star、fork 了某些项目就会出现在你的时间线里。

点头像——your profile 可以进入个人主页

![](http://ww4.sinaimg.cn/large/6bf00bd8gw1f67bhfz93nj20v60keqa7.jpg)

## GitHub 基本概念

---

上面认识了 GitHub 的基本面貌之后，你需要了解一些 GitHub 的基本概念，这些概念是你经常会接触并遇到的。

**Repository** :仓库的意思，即你的项目，你想在 GitHub 上开源一个项目，那就必须要新建一个 Repository ，如果你开源的项目多了，你就拥有了多个 Repositories 。

**Issue** :问题的意思，举个例子，就是你开源了一个项目，别人发现你的项目中有bug，或者哪些地方做的不够好，他就可以给你提个 Issue ，即问题，提的问题多了，也就是 Issues ，然后你看到了这些问题就可以去逐个修复，修复ok了就可以一个个的 Close 掉。

**Star** :这个好理解，就是给项目点赞，但是在 GitHub 上的点赞远比微博、知乎点赞难的多，如果你有一个项目获得100个star都算很不容易了！

**Fork** :你开源了一个项目，别人想在你这个项目的基础上做些改进，然后应用到自己的项目中，这个时候他就可以 Fork 你的项目，这个时候他的 GitHub 主页上就多了一个项目，只不过这个项目是基于你的项目基础（本质上是在原有项目的基础上新建了一个分支，分支的概念后面会在讲解Git的时候说到），他就可以随心所欲的去改进，但是丝毫不会影响原有项目的代码与结构。

**Pull Request** :发起请求，这个其实是基于 Fork 的，还是上面那个例子，如果别人在你基础上做了改进，后来觉得改进的很不错，应该要把这些改进让更多的人收益，于是就想把自己的改进合并到原有项目里，这个时候他就可以发起一个 Pull Request（简称PR） ，原有项目创建人就可以收到这个请求，这个时候他会仔细review你的代码，并且测试觉得OK了，就会接受你的PR，这个时候你做的改进原有项目就会拥有了。

**Watch** :这个也好理解就是观察，如果你 Watch 了某个项目，那么以后只要这个项目有任何更新，你都会第一时间收到关于这个项目的通知提醒。

**Gist** :有些时候你没有项目可以开源，只是单纯的想分享一些代码片段，那这个时候 Gist 就派上用场了！