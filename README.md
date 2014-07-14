f2ltest
=======

F2L的软件辅助训练


F2L是CFOP方法的一个步骤,同时对好魔方的前两层。

###本软件功能

- 训练对魔方角块的颜色敏感性，看到角块的两个面，立即反应出第三个面的颜色，并据此迅速找到和角块配对的棱块。

- 训练对标准F2L的41种形态从四个方向上的解决能力，同时还训练运用空槽的能力。

###FAQ

1. 如何使用其他底色？

编辑 3color.html:
	// 白底
	var scheme = "yrbwog";
	// 黄底
	//var scheme = "wobyrg";
	// 蓝底
	//var scheme = "gwrbyo";
	// 绿底
	//var scheme = "bwogyr";
	// 红底
	//var scheme = "obwrgy";
	// 橙底
	//var scheme = "rgwoby";

将需要的底色取消注释即可.

2. 如何使用非联网版本？

新建一个目录img,将subjecturls文件中的url下载到img目录中.
然后编辑 3color.html:
	var imgurl = "http://cube.crider.co.uk/visualcube.php?size=" + imgsize + "&fmt=png&bg=EEE";
改为
	var imgurl = "img/visualcube.php@size=" + imgsize + "&fmt=png&bg=EEE";
=======
