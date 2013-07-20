emacs.d
=======
#插件安装及配置

安装yasnippet：(模板功能)

在~/.emacs.d/emacs目录下解压。

安装auto-complete:(自动补全)

在~/.emacs.d/emacs目录下解压,然后make，编译结束后该文件夹不能被移动。

安装cedet:

在~/.emacs.d/emacs目录下解压,然后看INSTALL安装。

安装ecb:
在~/.emacs.d/emacs目录下解压。

将.emacs放在~/目录下，将emacs文件夹放到~/.emacs.d目录下。


#基本操作

向上移动一行：ctrl+p

向下移动一行：ctrl+n

向前移动一位：ctrl+b

向后移动一位：ctrl+f

移到行首：ctrl+a

移到行末：ctrl+e

插入一行：ctrl+o

删除一行：ctrl+k

保存：ctrl+x ctrl+s

另存为：ctrl+x ctrl+w

复制：alt+w

剪切：ctrl+w

粘贴:ctrl+y

退出：ctrl+x ctrl+c

进入shell:alt+x  shell

gdb调试：alt+x   gdb

编译：alt+x   compile

插入注释：ESC+;

man 手册: f1

info信息：ctrl-f1

查找字符串：f3

关闭当前缓冲区：alt+f3

多个文件切换，显示文件列表，相当与TagList：f4

打开ecb：ctrl+f4

隐藏/显示工具栏：f5

隐藏/显示菜单栏：ctrl+f5

gdb调试：f6

编译程序：f7

在另一个buffer打开eshell ：f8

在当前buffer打开eshell:  ctrl+f8

eshell清屏：shift+f8

重新打开一个eshell：ctrl+u,ctrl+f8

调用dired命令：ctrl+f9

在其他窗口之间旋转:f9

移动ecb窗口：alt+left/right/up/down

隐藏/显示ecb窗口：f11/shift+f11

显示日历：ctrl-f11

调到函数定义：f12

跳回：shift+f12

goto-line: alt+g

关闭当前窗口：alt+4

关闭其他窗口：alt+1

水平分割窗口：alt+2

垂直分割窗口：alt+3

切换到其他窗口：alt+0

折叠整个buffer的代码：ctrl+-

展开整个buffer的代码：ctrl+=

折叠一个函数的代码：ctrl+_

展开一个函数的代码：ctrl++

yas模板功能：输入关键字+tab

eg:inc+tab  ==  `#include <xxxx>`
目前默认的模板有：include/main/for/if/do...while/struct/once/printf/class/using/

俄罗斯方块：alt+x,tetris

doctor: alt+x, doctor  （就是一个简单的人机对话程序）