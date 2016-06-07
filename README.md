# mentohust-for-merlin
mentohust for asuswrt-merlin，支持ARM（浙江理工大学锐捷+l2tp测试通过）+Mipsel架构（未测试）

## 一点说明
MentoHUST是一个支持Windows、Linux、Mac OS下锐捷认证的程序（附带支持赛尔认证）,这里po出交叉编译后的程序，适应于运行asuswrt-merlin系统的路由器

ARM架构实测可用（Linksys EA6400， Firmware:380.57_X6.5），Mipsel尚未经测试

sourcecode有改动，详情请参阅./cross-compilation-sourcecode-based-on-mentohust-0.3.1/src/README.md

使用前需注意在路由器管理界面 系统管理->系统设置中启用路由器jffs分区

使用时请将本项目中jffs目录下文件增量更新至路由器jffs目录

**烦请务必注意增量更新nat-start中设置，不要直接覆盖，以免丢失原设置**

详细介绍、调试、运行步骤请移步 [先前po在koolshare的帖子](http://koolshare.cn/thread-9324-1-1.html) 

## 关于编译
* 编译环境：CentOS 7.0
* libpcap版本：1.0.0
* mentohust版本：0.3.1
* ARM架构使用的编译工具链：hndtools-arm-linux-2.6.36-uclibc-4.5.3
* Mipsel架构使用的编译工具链：K26/hndtools-mipsel-uclibc-4.2.4

## 其他
* 感谢前辈们的努力与付出，同时同情一下在看这个的你：）
* 最近在做闪讯的编译，不过马上毕业，估计要流产
* 有问题请留言
* 希望你我不会沦为令后来者讨厌的程序员
