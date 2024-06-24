# Omega-net
一个omega网络模拟器，能自定义网络规模，模拟单播、组播、广播路径并生成图片。

# QuickStart
除了README.md，项目目前包含两个文件，其功能相同，不过omega.ipynb的运行额外需要有Jupyter Notebook软件，而omega.py是常规的python文件。<br>
运行需要一个包含numpy、matplotlib包的python3.11版本的环境，用户根据程序提示消息进行输入可以自定义网络输入规模和想要实现的连接，程序运行结束后会提供一张对应Omega网络的图片。<br>

# TODO
-冲突检测<br>
-多对多组播模拟<br>
-更改绘图方式，让它更自适应<br>
-打包，使没有python环境的用户也可一键使用

# References
https://github.com/vijendra/Omega-network<br>:本项目参考该项目的omega.c文件，并将其改写为使用python实现
