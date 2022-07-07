[TOC](文章目录)

<a name="Menutop" >顶部</a>

# [目录](#目录)

- [简介](#简介)
- [GitTips](#GitTips)
  - [git gc](#git_gc)
  - [git push](#git_push)
- [LinuxTips](#LinuxTips)
  - [udhcpc](#udhcpc)
- [VimTips](#VimTips)
  - [移动光标](#移动光标)
  - [进入和退出](#进入和退出)
  - [删除](#删除)
  - [撤销](#撤销)

# <a name="GitTips" >**GitTips**</a>

​	

~~~c
git init
git add 
git commit
git remote add origin http://name:password@gitee.com/zhaochengjie/gitname.git
~~~





## <a name="git gc" >**git_gc**</a>

- ~~~c 
  git gc --prune=now 

​				解决本地缓存过大的问题，清理本地缓存

## <a name="git push" >**git push**</a>

- ~~~c
  git push --force origin master
  ~~~

  强制推送覆盖到远程仓库

  





# <a name="LinuxTips" >**LinuxTips**</a>

​	

## <a name="udhcpc" >**udhcpc**</a>

- ~~~c 
  udhcpc -i usb1
  ~~~

​			动态获取ip配置

udhcpd就是终端设备作为DHCP服务器

udhcpc就是终端设备作为DHCP客户端





# <a name="VimTips" >**VimTips**</a>

## <a name="移动光标" >**移动光标**</a>

- h 的键位于左边，每次按下就会向左移动;

  l 的键位于右边，每次按下就会向右移动;

  j 键看起来很象一支尖端方向朝下的箭头;

  k键每次按下就会向上移动.

## <a name="进入和退出" >**进入和退出**</a>

- 首先确保自己在正常模式（ 按<ESC>键）

然后按键盘上按下”shift+：”，输入“q！”，回车

这种方式的退出编辑器会丢弃您进入编辑器以来所做的改动

输入“wq”则会保存所做的改动。



## <a name="删除" >**删除**</a>

- 输入dd删除该行。
- 输入ndd删除n行，n代表删除以下多少行。



## <a name="撤销" >**撤销**</a>

- 输入u撤销最后一次执行的命令。
- 输入Ctrl+R可以重做被撤销的命令。
