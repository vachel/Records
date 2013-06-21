vim的常用快捷键

F4切换编辑窗和文件列表窗，分屏显示
使用CTRL + hjkl 切换窗口
:Tlist打开函数列表窗口
F12  创建ctags
F11  创建cscope
:cs find e 字符串   查找字符串不区分大小写
:cs find s 字符串   查找字符串区分大小写
CTRL + t 返回上一次跳转点
CTRL + ] 跳转到函数实现的地方
拆分窗口：CTRL + w，然后 s 

gg 光标到文件头
G  光标到文件尾

更多vim指令可以通过linux下的vimtutor程序来练习；
而快捷方式的使用和自定义可以查看自己的主目录下的隐藏文件.vimrc，其中包含了各种快捷方式配置。

:cs find s function_name  查找C语言符号，即查找函数名、宏、枚举值等出现的地方
:cs find g function_name 查找函数、宏、枚举等定义的位置，类似ctags所提供的功能  
:cs find d function_name  查找本函数调用的函数
:cs find c function_name 查找调用本函数的函数   这个也比较有用处
:cs find t function_name   查找指定的字符串
:cs find e function_name  查找egrep模式，相当于egrep功能，但查找速度快多了
:cs find f function_name   查找并打开文件，类似vim的find功能
:cs find i function_name   查找包含本文件的文件