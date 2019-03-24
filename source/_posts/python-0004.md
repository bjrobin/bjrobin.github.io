---
title: 【python-0004】python安装
date: 2019-03-23 17:46:53
tags: python
---
## 安装
打开python的官方网址：https://www.python.org/
![](/blog/images/python_0004_01.png) 
从菜单中选择Dowloads再点击Windows，进入页面：Python Releases for Windows
![](/blog/images/python_0004_02.png) 
找到Python 3.7.2这一段：
选择：Download Windows x86-64 executable installer
![](/blog/images/python_0004_03.png) 
运行下载到的文件
特别要注意勾上Add Python 3.7 to PATH
![](/blog/images/python_0004_04.png) 
然后点“Install Now”（默认安装）即可完成安装。
![](/blog/images/python_0004_05.png) 
安装成功
![](/blog/images/python_0004_06.png) 
运行Python

安装成功后，打开命令提示符窗口，敲入python后，会出现两种情况：
## 安装成功
情况一：安装成功
![](/blog/images/python_0002_02.png) 
看到上面的画面，就说明Python安装成功！
你看到提示符>>>就表示我们已经在Python交互式环境中了，可以输入任何Python代码，回车后会立刻得到执行结果。
现在，输入exit()并回车，就可以退出Python交互式环境（直接关掉命令行窗口也可以）。
## 安装错误
情况二：得到一个错误：
<code>'python'不是内部或外部命令，也不是可运行的程序或批处理文件。</code>
这是因为Windows会根据一个Path的环境变量设定的路径去查找python.exe，如果没找到，就会报错。
如果在安装时漏掉了勾选Add Python 3.7 to PATH，那就要手动把python.exe所在的路径添加到Path中。
如果你不知道怎么修改环境变量，建议把Python安装程序重新运行一遍，务必记得勾上Add Python 3.7 to PATH。


