# web-learning
我的web学习之路
1.Mac 终端创建ssh key并添加到GitHub成功

2.上传到github命令：
git add .
git commit -m "first ci"
git push origin master

 - 错误代码：```IndentationError：预计有一个缩进块``
错误原因：Python的语言是一款对缩进非常敏感的语言：
```
如果xxxxxx：
（空格）XXXXX
或者
def xxxxxx：
（空格）XXXXX
还有
对于xxxxxx：
（空格）XXXXX
一句话有冒号的下一行往往要缩进，该缩进就缩进
```
