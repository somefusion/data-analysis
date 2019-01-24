##*一、更改Jupyter notebook的工作空间*

进入工作目录文件夹
键盘Shift+鼠标右键->在此处打开命令窗口-> 在弹出的命令窗口中输入：Jupyter Notebook 
Jupyter被打开，定位到当前目录！

##*二、Jupyter的各种快捷键*
执行当前cell，并自动跳到下一个cell：Shift Enter
执行当前cell，执行后不自动调转到下一个cell：Ctrl-Enter
为一行或者多行添加/取消注释：Crtl /
快速跳转到首个cell：Crtl Home
快速跳转到最后一个cell：Crtl End

##*三、Jupyter Notebook如何导入代码*
在需要导入该段代码的cell中输入
%load test.py      #test.py是当前路径下的一个python文件
利用快捷键“Shift+Enter”
运行后，%load test.py被自动加入了注释符号#，test.py中的所有代码都被load到了当前的cell中

##*四、Jupyter运行python文件*
%run file.py
file.py为要运行的python程序，结果会显示在该cell中 

##*五、Jupyter一些其他琐碎用法*
jupyter的cell可以作为unix command使用
获取current working directory     current_path = %pwd      这样得到的current_path就是当前工作路径的字符转
使用Matplotlib绘图     %matplotlib inline
Jupyter中的Markdown语法，Markdown语法此处插入链接。
jupyter中设置link
<a id='the_destination'></a>
