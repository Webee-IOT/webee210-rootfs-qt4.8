###webee210-rootfs-qt4.8的开发指南

如果想参与本项目的开发,请确保你已经看过[网蜂开发者社区简介](https://github.com/Webee-IOT/Document/blob/master/%E7%BD%91%E8%9C%82%E5%BC%80%E5%8F%91%E8%80%85%E7%A4%BE%E5%8C%BA%E7%AE%80%E4%BB%8B.md),并且已经拥有了上面提到的`github`和`gmail`.你只需要从[webee210-rootfs-qt4.8](https://github.com/iZobs/webee210-rootfs-qt4.8) fork这个项目,从__自己主页__git clone 下来，并且加入这个邮件列表就可以了:[webee-os](https://groups.google.com/d/forum/webee-os).该项目有两个分支一个为`master`,另一个为
`dev`.`dev`分支为开发分支,有TODO列表正在开发的功能,bug也比较多.`master`是稳定版,拥有`TODO`列表已经完成的功能,你可以在这条分支上debug.文件系统的应用程序源代码将存放于该工程的`app-src`目录下.

例如下面的TODO:

###TODO

- 编写一个简单的qt启动器，WeBee_Launcher
- 移植一个支持中英文的Qt输入法
	

###讨论

发送E-mail到`webee-os@googlegroups.com`.注意邮件的主题的格式,用[]做标签.如讨论BUG,发送email的主题如下: 

    send:webee-os@googlegroups.com
    topic:[Bug]uboot的菜单页面出现乱码


###git使用tips

- [如何同步fork源仓库的代码](https://help.github.com/articles/syncing-a-fork)
- [git分支管理策略](http://www.ruanyifeng.com/blog/2012/07/git.html)
- [git权威指南](http://www.worldhello.net/gotgit/)


###项目维护人              

__izobs : ivincentlin@gmail.com__
