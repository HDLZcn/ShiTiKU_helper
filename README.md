# ShiTiKU_helper
在试题库里寻找剪贴板中的内容，并返回对应的选项和答案。/Look for the contents of the clipboard in the test bank and return the corresponding options and answers.

你好！欢迎来到Python3的世界！我也是和你一样遇到了题库和试题选项对不上的情况，所以就搞了一个这个小脚本来偷懒~

不可以用她来做坏事哦！

========================

update：
在说明文件里添加了新的内容，优化易读性
在仓库里加入了python3的软件
2019年4月18日 09点05分

========================



准备步骤：

1 此软件来的匆忙，所以运行环境依赖于Python3的IDLE，如果你有py3就跳过。

	##没有的话点击文件夹里的【python-3.7.2-amd64-webinstall】自动安装。选install now 并点上那个add python as Path的勾。//这边需要你自己去装py3
	###不过如果你没点勾也没关系，参考这个帖子自己贴上PATH就好
	https://www.cnblogs.com/qiyeshublog/archive/2012/01/24/2329162.html 做第一步即可。
	
2 需要安两个库：

	##按win+r 输入CMD
	##复制下面的两行（分两次！每次按下回车之后等进度条走完就行，几百KB很小的。
	pip install openpyxl
	pip install pyperclip
	
3 应该就行了……吧？如果你有自己的题库，就粘贴到这个xlsx文件里，没有的话就不用动。

=========================

使用方法：

1 假如现在你要做单选题，那么就打开xlsx-点击单选题所在的sheet-随便点击一个单元格-保存
2 打开网站，选择第一个题内容让他变蓝，ctrl+C
3 然后右键点击文件夹中findyou.py，选用IDLE打开【edit with IDLE】
4 按F5
5 这时应该就会跳出第一个题的答案了
6 重复第二步和第五步直到单选题做完
7 回到第一步一下下，选下一个sheet
8 再重复第六步直到所有题做完
9 然后感叹一句“懒惰是第二推动力”

=========================

异常：
最常见的异常就是没有这个题，解决办法是复制少一点、不复制括号等符号和空格、求助搜索引擎……
=========================
我的公众号：hdlzhdlz 欢迎关注！
