
Vim具有6种基本模式和5种派生模式：
~普通模式(Normal mode)
~插入模式(Insert mode)
~可视模式(Visual mode)
~选择模式(Select mode)
~命令行模式(Command line mode)
~Ex模式(Ex mode)

在普通模式下使用下面的键将进入插入模式，并可以从相应的位置开始输入

1命令 说明
i 在当前光标处进行编辑
I 在行首插入
A 在行末插入
a 在光标后插入编辑
o 在当前行后插入一个新行
O 在当前行前插入一个新行
cw 替换从光标所在位置后到一个单词结尾的字符

2命令行模式下退出vim

从普通模式输入:进入命令行模式，输入wq回车，保存并退出编辑

以下为其它几种退出方式：

命令 说明
:q! 强制退出，不保存
:q 退出
:wq! 强制保存并退出
:w <文件路径> 另存为
:saveas文件路径 另存为
:x 保存并退出
:wq 保存并退出

3普通模式下删除vim文本信息

进入普通模式，使用下列命令可以进行文本快速删除：

命令 说明
x 删除游标所在的字符
X 删除游标所在前一个字符
Delete 同x
dd 删除整行
dw 删除一个单词（不适用中文）
d$或D 删除至行尾
d^ 删除至行首
dG 删除到文档结尾处
d1G 删至文档首部
除此之外，你还可以在命令之前加上数字，表示一次删除多行，如：

2dd表示一次删除2行
