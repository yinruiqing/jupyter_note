# Jupyter notebook 的使用


##为什么使用 Jupyter Notebook
1. Jupyther notebook 可以把代码、图像、注释、公式和图放到一个文件里。比较直观。
2. 可以安装在个人电脑或者任何服务器上通过远程连接


##常用操作
* 新建文件夹
* 新建一个 notebook
* 重命名
* 插入一个 cell
* cell 的模式
* markdown
* 移动 cell
* 复制粘贴 cell
* 删除
* 撤销删除
* 合并 cell
* 运行 cell
* 全部运行
* 保存


##常用快捷键
Jupyter Notebook 有两种不同的键盘输入模式：

**编辑模式**：在这个模式下你可以在 cell 中输入编辑代码或文字。这个模式下 cell 的边框饰绿色的。

快捷键               | 功能              | 
--------------------|------------------|
⇥  Tab键            | 代码补全 和 缩进    | 
⌘↑                  | 去 cell 的最开始   | 
⌘↓                  | 去 cell 的末尾    | 
⌃⇧-                 | 分隔当前 cell     |
⌥ 鼠标               | 多光标           |
⇧↩                  | 运行当前选中的 cell 并选中下一个 cell  | 
⌃↩                  | 运行当前选中的 cell | 
⌥↩                  | 运行当前选中的 cell 并在下面插入一个 cell     | 
⌘⇧P                 | 搜索命令          | 
⌘S                  | 保存             | 
Esc                 | 进入命令模式       | 

**命令模式**：在这个模式下你无法在 cell 中输入文字，但可以通过键盘来实现 notebook 的常用操作。这个模式下 cell 的边框是蓝色的。

快捷键               | 功能              | 
--------------------|------------------|
Y                   | 代码模式          | 
M                   | markdown         | 
⇧↑                  | 选中当前和上一个 cell| 
⇧↓                  | 选中当前和下一个 cell |
A                   | 在上面插入一个 cell   |
B                   | 在下面插入一个 cell  | 
X                   | 剪切当前选中的 cell | 
C                   | 复制当前选中的 cell     | 
V                   | 粘贴cell         | 
D，D                 | 删除 cell             | 
⇧M                  | 合并 cell             | 
L                   | 显示行号               | 
F                   | 查找和替换             | 
O                   | 隐藏或者显示输出        | 
H                   | 显示快捷键             | 
I,I                 | 中断 kernel           | 
↩                  | 进入编辑模式            |



##魔术命令
魔术命令              | 功能              | 
--------------------|------------------|
%lsmagic            | 列出所有的魔术命令   | 
？                   | 帮助信息          | 
%run                | 执行 python 文件   | 
%load               | 倒入外部脚本文件    | 
%who                | 列出所有变量 并且后面可以加类型进行过滤 |
%whos               | 列出所有变量名称、类型、值 |
%time               | 计算语句执行时间   |
%prun               | 计算程序中每个函数消耗的时间 | 
%timeit             | 计算单行代码的平均执行时间 | 
%%timeit            | 计算 cell 代码的平均执行时间 | 
%%writefile         | 将 cell 里的语句写入指定文件 | 
%reset              | 清除变量               | 
%matplotlib inline  | 默认在notebook中显示图像   | 
%load_ext autoreload %autoreload 2 | 自动导入外部模块   | 
%automagic          | 设置输入魔术命令时是否键入%前缀，on(1)/off(0)| 
%debug              | 调试               | 


Debug 操作           | 功能              | 
--------------------|------------------|
(h)elp              | 显示命令列表   | 
(p)rint             | 打印变量          | 
(p)retty(p)rint     | 打印变量，适用于链表，字典   | 
(n)ext line         | 执行当前行，并进入下一行   | 
(u)p／(d)own         | 在函数调用栈向上或向下移动    | 
(s)tep              | 单步进入函数 |
c(ont(inue))        | 恢复程序的执行 |
(r)eturn            | 计算语句执行时间   |
b(reak) n           | 在当前文件第 n 行设置一个断点  |

[更多魔术命令](http://ipython.readthedocs.io/en/stable/interactive/magics.html)

## 分享 notebook
* 使用菜单项 File > Download as html 或者 pdf
* 使用 [gist](https://gist.github.com/) 或 [github](https://github.com) 分享 notebook
* 将 notebook 保存到 [github](https://github.com) 或者 [Dropbox](https://www.dropbox.com) 中，然后将链接放到 [nbviewer](http://nbviewer.jupyter.org/)。 

## 其它功能
* 插入图片，音乐，html代码，视频
* [连接远程的 Jupyter 服务器](http://danielhnyk.cz/running-ipython-notebook-different-computer/)
* [制作幻灯片](http://www.slideviper.oquanta.info/tutorial/slideshow_tutorial_slides.html#/1)
* [28 个Jupyter Notebook 技巧](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
