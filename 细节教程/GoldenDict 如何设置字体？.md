刚使用 GoldenDict 的朋友会问一些很基础的问题，今天有朋友问“GoldenDict 如何设置字体”。
其实已经有一些帖子了，我这里再发一个，“精心”录制了 gif ，希望能对新人有所帮助。这些简单的问题，真·大神从不讲，我也是一步一步知晓这些细节的，知道新人的苦，新人的累，所以也不厌其烦，写了些看上去很“弱”的入门贴，希望对大家有所帮助。

![GoldenDict 设置字体.gif](http://upload-images.jianshu.io/upload_images/4087589-42ba725ff393efec.gif?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 文字版步骤：
1.  菜单栏，【帮助】->【配置文件夹】，如果你按照这里的步骤第 3 步做了的话：
	-  “GoldenDict 下载、安装、使用入门教程[Windows 版]” https://www.jianshu.com/p/e124979c887a ，第 3 步 “新建 portable 文件夹”
“配置文件夹”就是 portable 文件夹。

2. 新建两个 txt 文本文档，
- 新建文本文档.txt
- 新建文本文档 - 副本.txt

Windows 10 下，文件资源管理器注意勾选“查看”->“文件扩展名”

3. 将那两个 txt 分别更名为 article-style.css 和 qt-style.css 
一定注意，文件扩展名 .txt 也要删除并修改为 .css

4. 打开 article-style.css 文件，把下面的内容复制、粘贴进去，保存！

`* {
font-family: Arial, "Microsoft Yahei"!important;
}`

5. 打开 qt-style.css  文件，把上面的内容复制、粘贴进去，保存！


我这里只是简单示例， article-style.css 和 qt-style.css 可以设置很多东西，GoldenDict 的界面定制，魔法几乎全在这两个 css 里。

6. 【文件】->【重新扫描文件】，或者直接快捷键 Ctrl + F5 ， article-style.css 和 qt-style.css  这两个 css 就生效了，仔细看看，是不是字体变了？
- 左侧默认的英文字体是 Tahoma ，中文字体是宋体（SimSun）;
- 右侧的英文字体是我们通过 article-style.css 设置的 Arial，中文字体是微软雅黑（Microsoft YaHei），注意 css 里直接写字体的汉字名称“微软雅黑”可能没用，要用 "Microsoft YaHei" 且用英文引号括起来。

![前-后.png](http://upload-images.jianshu.io/upload_images/4087589-ed55dcd26660f6a7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

CSS 入门简单，但是又可以很复杂，有很多坑，我也只会很简单的。更多的个性定制方案，还需要大家自行摸索。

不过，我是折腾来折腾去，觉得上面的 article-style.css 和 qt-style.css 已经够用了，其他的设置都是 GoldenDict 默认。
-EOF-
