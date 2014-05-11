###参与webee210-rootfs-qt4.8的开发

如果你想参与本__webee210-rootfs-qt4.8__的开发,请用力hit下面的链接:

[webee210-uboot开发指南](https://github.com/iZobs/webee210-uboot/blob/master/Develop-doc.md)

###关于
这是网蜂webee210的带qt4.8.5软件库的文件系统，这个文件系统里将存放部分二进制驱动和部分应用程序。
###UPDATE
__2014-5-1__
- 升级qt软件库为qt4.8.5
- 添加qt_test UVC摄像头测试QT程序
- 添加lrz,lsz串口上传和下载命令
- 添加ft5306和ft5206的profile配置

###TODO
- 编写一个简单的qt启动器，webee_Launcher
- 移植一个支持中英文的qt输入法
###编译

         @ ./mkyaffs2image-512M rootfs_qt4.8 system.img


