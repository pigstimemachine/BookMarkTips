[TOC](文章目录)

<a name="Menutop" >顶部</a>

# [目录](#目录)

- [简介](#简介)
- [GitTips](#GitTips)
  - [git gc](#git_gc)
  - [git push](#git_push)
- [LinuxTips](#LinuxTips)
- [ShellTips](#ShellTips)
  - [udhcpc](#udhcpc)
- [VimTips](#VimTips)
  - [移动光标](#移动光标)
  - [进入和退出](#进入和退出)
  - [删除](#删除)
  - [撤销](#撤销)
  - [定位](#定位)
  - [外部命令](#外部命令)
- [ElectronicsTips](#ElectronicsTips)
  - [晶振](#晶振)


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



# <a name="ShellTips" >**ShellTips**</a>

​	

## <a name="udhcpc" >**udhcpc**</a>

- ~~~c 
  udhcpc -i usb1
  ~~~

​			动态获取ip配置

udhcpd就是终端设备作为DHCP服务器

udhcpc就是终端设备作为DHCP客户端



## <a name="dir" >**dir**</a>

- ls(list)：会显示不同类型的文件的颜色

  dir(directory)：不显示不同文件类型的文件颜色，所有文件都是一种颜色

  但两种指令的作用都是显示当前目录下的文件

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

## <a name="定位" >**定位**</a>

- 输入大写 G 可以使得当前光标直接跳转到文件最后一行。
-  输入 gg 可以使得当前光标直接跳转到文件第一行。

- 在正常模式下输入 / 字符。您此时会注意到该字符和光标都会出现在屏幕底 部，这跟 : 命令是一样的。接着输入 errroor <回车>。那个errroor就是您要查找的字符串。要查找同上一次的字符串，只需要按 n 键。要向相反方向查找同上一次的字 符串，请输入大写 N 即可。如果您想逆向查找字符串，请使用 ? 代替 / 进行。

## <a name="外部命令" >**外部命令**</a>

- 输入 :! 然后紧接着输入一个外部命令可以执行该外部命令按下我们所熟悉的 : 命令使光标移动到屏幕底部。这样您就可以输入一行命令了。接着输入感叹号 ! 这个字符，这样就允许您执行外部的 shell 命令了。我们以 ls 命令为例。输入 !ls <回车> 。该命令就会列举出您当前目录的 内容，就如同您在命令行提示符下输入 ls 命令的结果一样。如果 !ls 没起 作用，您可以试试 :!dir 看看。



# <a name="ElectronicsTips" >**ElectronicsTips**</a>



## <a name="晶振" >**晶振**</a>



- 电子线路中的晶体振荡器也分为无源晶振和有源晶振两种类型。无源晶振与有源晶振的英文名称不同，无源晶振为crystal（晶体），而有源晶振则叫做oscillator（振荡器）。无源晶振是有2个引脚的无极性元件，需要借助于时钟电路才能产生振荡信号，自身无法振荡起来，所以“无源晶振”这个说法并不准确；有源晶振有4只引脚，是一个完整的振荡器，其中除了石英晶体外，还有晶体管和阻容元件，因此体积较大。
- 
