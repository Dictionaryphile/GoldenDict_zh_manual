本文最后更新：2018年1月23日  
- [GoldenDict 中文用户手册](http://www.jianshu.com/p/15dcd19ec8be)  

推荐阅读：  
- [[2017-01-15] 不用 GoldenDict 的 10 个理由](http://mp.weixin.qq.com/s/HzZZhyyHMb0DpQ4AYOLzlA)  
- [[2017-01-21] GoldenDict 全文搜索几例](http://mp.weixin.qq.com/s/gHMJrVG_bmGw142fEEtNeQ)  

**说明**：  
- 如有链接无法打开，不妨尝试科学上网。  
- 请耐心一些。从小到大，用筷子吃饭需要学习，走路需要学习，骑车需要学习，工具软件也需要学习；会吃饭，会走路，会骑车，那学会使用工具软件，自然也不在话下，只需要耐心一点。捷径都有陷阱，某些傻瓜式、一路确定就安装好了、点开就可以查词的软件，有它们的用户群，你既然选择读这篇短文，就说明你对自己还是有一定要求的。  

Windows 下我推荐的（我也是这么做的）下载、安装、使用步骤如下，肯定有其他使用办法，我这里用自己的操作步骤举例而已，方便新手入门。  

# ▌入门分 8 步  

1. [下载 GoldenDict](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/)  
2. 解压  
3. 新建 portable 文件夹  
4. 复制（或剪切）词库文件到 content 文件夹  
5. 点击 GoldenDict.exe ，启动  
6. 关闭全文搜索  
7. 开始查词  
8. 对词典进行分组  

---  

##**第一步**， 下载软件包  
访问这个可靠的 [ GoldenDict 软件包发布地址](http://sourceforge.net/projects/goldendict/files/early%20access%20builds/)  
► **操作理由**：  
	0. [官网](http://goldendict.org/download.php)提供的版本，是很旧很旧的版本（8 年前的版本），不支持 mdx/mdd ，不支持全文搜索。  
	1. 因为 sourceforge.net 更容易访问一点  

下载【[GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486).zip](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/GoldenDict-1.5.0-RC2-209-gfe9312e_%28QT_486%29.zip/download) 】【2017-12-10 32.9MB】这个文件 （当然，可以选择其他版本[推荐下载最新版]，我这里只是拿这个版本做个例子，建议下载 zip 或 7z 格式的压缩包，**不建议**下载 exe 可执行文件）。  
我目前用的版本是 [GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_563)(64bit).7z](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/Qt5-based/64bit/GoldenDict-1.5.0-RC2-209-gfe9312e_%28QT_563%29%2864bit%29.7z/download)，我也**推荐 Windows 下用 [QT5 版本](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/Qt5-based/)**，QT4 版本中文字体显示有问题，无论如何设置，都只能是操作系统默认的（比如不太好看的宋体）。  

![1-1.png](http://upload-images.jianshu.io/upload_images/4087589-12632aae4f28b351.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  



##**第二步**，解压  
► **操作理由**：不解压没法用啊。  
我这里解压到 【D:\GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486)】，解压出来的文件夹占用空间约 87 MB ，文件路径、情况如下图：  
![2-1.png](http://upload-images.jianshu.io/upload_images/4087589-0ba3fb280112ae2b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  



## 第三步，新建 portable 文件夹  
在解压得到的目录下（我这里是 D:\GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486)\GoldenDict），新建一个文件夹，名为 portable 。  
► **操作理由**：这样做，**不是必须的**，但是，我强烈推荐这么做，是为了让 GoldenDict 变为绿色、便携版（可直接拷到优盘、移动硬盘里，即插即用），假如不在此处新建  portable 文件夹，那么 GoldenDict 的索引文件（词典数量庞大，索引文件体积也会水涨船高），将会堆积在系统盘（一般是 C 盘）的某个位置，建立了 portable 文件夹，索引文件会存放在 portable 文件夹下的 index 子目录下，方便管理；当然，不新建 portable 文件夹，也有它的道理、好处，可以指定加载某目录下的词库文件，不一定非得把所有词库文件（夹）{或文件（夹）快捷方式}复制到 content 文件夹下，但是我个人觉得，还是新建 portable 文件夹这种方式更好。  
![3-1.png](http://upload-images.jianshu.io/upload_images/4087589-a135c88409d2016e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


## 第四步，复制（或剪切）词库文件到 content 文件夹  
复制（或剪切）想要使用的词库文件到 content 文件夹下，为了更便于管理，建议按照个人方式，建立子文件夹。  
我这里把一部词典，拷到下面目录 【D:\GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486)\GoldenDict\content\英汉词库】  
► **操作理由**：因为我们在第三步， 建立了 portable 文件夹，所以**必须**把词库文件（或词库文件或文件夹的快捷方式）复制到 content 文件夹下，GoldenDict 才能加载词库。  
![4-1.png](http://upload-images.jianshu.io/upload_images/4087589-d94c7ec6c41c2e4e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


## 第五步，点击 GoldenDict.exe ，启动  
点击 GoldenDict.exe ，我这里位于【D:\GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486)\GoldenDict】  
你可以选择为 GoldenDict.exe 建立桌面快捷方式或者固定在任务栏，方便快速访问。  
如图，提示“正在索引词典，请稍候”，如果词典数量较多，这个过程会比较长。  
![5-1.png](http://upload-images.jianshu.io/upload_images/4087589-5615b60a0ee6925d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
GoldenDict 启动后，是这样的，貌似看上去不太好看，都是系统字体、字体渲染的原因。  
![5-2.png](http://upload-images.jianshu.io/upload_images/4087589-2125d9abf076a076.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


## 第六步，关闭全文搜索  
！！！非常关键、敏感的一步，问题最多的一步，最容易忽视的一步。  
点开【编辑】->【首选项】->【全文搜索】，按照自己的需求，选择关闭全文搜索或者选择仅对某一（或几）种格式的词典进行全文搜索。  
![image](http://upload-images.jianshu.io/upload_images/4087589-e77245107b605a0b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

看，GoldenDict 默认对所有词典进行全文搜索，不过一般用户其实用不上。  
![image](http://upload-images.jianshu.io/upload_images/4087589-20fec73b7af53772.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


我按照自己的选择，选择对 DSL 、MDict 格式词典进行全文搜索。  
![全文搜索设置](http://upload-images.jianshu.io/upload_images/4087589-fef8cb959eee3443.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

► **操作理由**： GoldenDict 默认对所有（格式）词库进行全文搜索，假如你直接一次性加载了大量词库，而电脑配置一般的话，你会发现，第一次打开 GoldenDict 很慢，查看任务管理器，GoldenDict 占用 CPU 很大，甚至达到 100 % （当然，我从来没遇到过这情况）。  
假如全文搜索对你不重要的话，那就在第一次打开 GoldenDict 时，迅速地前往【编辑】->【首选项】->【全文搜索】，关闭“全文搜索”（就是把前面的勾去掉）。  
假如你想体验全文搜索功能的话，那就找一个比较闲的时间，打开 GoldenDict ，让它慢慢地索引，比如睡觉前点开 GoldenDict，第二天醒来，一般说来，全文索引都进行完毕了。  

## 第七步，可以开始查词了。  
![image](http://upload-images.jianshu.io/upload_images/4087589-ac8d023e408170ce.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

**全文搜索**：  
![image](http://upload-images.jianshu.io/upload_images/4087589-635e82d20633af45.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


查看全部词头：  
![image](http://upload-images.jianshu.io/upload_images/4087589-d7ec80591b38c32d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
![image](http://upload-images.jianshu.io/upload_images/4087589-ead2526b227d8b00.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


## 第八步，对词典进行分组。  
【编辑】->【词典】  

我们可以看到，【词典来源】选项卡里的【添加】按钮是灰色的，这是因为我们在第三步，新建了 portable 文件夹。  
![image](http://upload-images.jianshu.io/upload_images/4087589-83a93d62651e858d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
![image](http://upload-images.jianshu.io/upload_images/4087589-37cafcb39bff9f11.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
![image](http://upload-images.jianshu.io/upload_images/4087589-2c42e607f6c16fe2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

……  

---  

建议更新版本，Windows 下更新办法是下载[这里](http://sourceforge.net/projects/goldendict/files/early%20access%20builds)合适的、自己需要的版本，（32位 or 64位）。  
具体办法有二：  
第一个办法，如果你使用的旧版本和选择下载的新版本是同样的 QT 版本以及同为 32bit 或 64bit ，那直接把新版本解压覆盖旧版本就行了（注意先退出 GoldenDict 再解压覆盖）  
第二个办法，解压新版本，把旧版本下面的 content & portable 文件夹剪切（或者复制）到新版本相应目录下。  

我自己更新版本，使用的是第二个办法，把旧版本下的 content & portable 文件夹**到新版本目录下，直接就可以继续用了，全文索引文件什么的，都在 portable 文件夹下，不需要重新费时索引。  

# 高阶  
【帮助】->【配置文件夹】，因为在入门步骤里，我建立了 portable 文件夹，所以我的“配置文件夹”就是 portable 文件夹。  
来到【D:\GoldenDict-1.5.0-RC2-209-gfe9312e_(QT_486)\GoldenDict\portable】  
新建两个文件：  
![新建 article-style.css 、qt-style.css ](http://upload-images.jianshu.io/upload_images/4087589-9c915154f3c92f83.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

- [article-style.css 示例](https://gist.github.com/Tvangeste/4663204)  
- [qt-style.css 示例](https://gist.github.com/Tvangeste/4574234)  

► 我自己使用的 article-style.css，就一行：  
```css  
* {font-family: Arial, SimSun, "Microsoft YaHei"!important; }  
```  
► 我喜欢的显示风格是 Lingvo（【编辑】->【首选项】->【界面】->【显示风格】）  
![GoldenDict界面语言、界面风格.png](http://upload-images.jianshu.io/upload_images/4087589-1dfeb0cbc55274e7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  


-EOF-  
