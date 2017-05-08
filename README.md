# 前三节总结
## 第一节课  
### 1.github是什么  
IT技术人员的社交网站（一个面向开源及私有软件项目的托管平台）

### 2.git是什么  
Git是一款免费、开源的分布式版本控制系统。

### 3.github的好处  
（1）GitHub上有很多的技术高手
（2）GitHub上可以接触到最新最前沿的IT技术
（3）可以观察到软件的开发过程，一览无遗，记录技术的发展
（4）GitHub是一个开源社区，我们可以寻找有兴趣的项目参与，增加项目经验
（5）不仅有托管项目还有文档教程

### 4.github的优势  
（1）只支持GIT
（2）完整协议支持
（3）在线文件编辑
（4）社交网络元素
（5）特色工作模式
（6）私有仓库托管
（7）Ruby on Rails

### 5.通过github年度报告让你记忆最深刻的信息有哪些  
JavaScript成为主流语言
bootstrap前端框架

### 6.github上有可以个人账号 还可以有（ ）账号  
企业和组织账号

### 7.github上面的两个组成要素是什么  
个人主页和仓库

### 8.github上两个重要页面  
个人主页和动态

### 9.主页菜单都包含什么  
概述  仓库  收藏  关注  被关注 

### 10.仓库的心跳线代表什么  
仓库的活跃程度，一条线代表一年，从今天以前的一年

### 11.star的作用是？  
star 的作用是收藏，目的是方便以后查找。

### 12.fork的作用是？  
fork 的作用是参与，目的是你增加新的内容，然后 Pull Request，把你的修改和主仓库原来的内容合并。

### 13.watch的作用是？  
watch 的作用是关注，目的是等作者更新的时候，你可以收到通知。

### 14.搜索结果分别有哪些类别  
repositories库   code代码   commits提交  issues问题  wikis维客  users用户  

### 15.你在github上挖到什么宝  
关注了几个技术大牛，star了几个项目  

## 第二节课  
### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  

new repository新存储库  import repository导入存储库   new gist代码片段  new organization新组织

### 2.如何能将仓库中的html文件直接解析成页面？  

Preview    Settings -> GitHub Pages -> Sourse -> master branch -> saves -> 点击地址

### 3.如何删除仓库  

仓库中找到setting  再找到Delete

### 4.Bash是什么操作系统的命令  

命令行

### 5.Pwd是什么命令  

打印当前目录

### 6.Cd是什么命令  

打印 复制

### 7.Echo是什么命令  

打印信息

### 8.配置git用户名的命令  

git config --global user.name=""

### 9.配置邮箱的命令  

git confiig --global user.email=""

### 10.命令行换行方式  
/

### 11.命令行终结方式  

ctrl+c

### 12.使用命令行比GUI方式有何优势  



### 13.提交到本地仓库时为什么有暂存区  

方便修改

### 14.新建代码仓库的命令  

git init

### 15.git clone [url] 这个命令的作用是  

github远程克隆到本地

### 16.添加指定文件到暂存区的命令  

git add[file1][file2]

### 17.删除工作区文件，并且将这次删除放入暂存区的命令  

git rm [file1] [file2]

### 18.改名文件，并且将这个改名文件放入暂存区的命令  

git mv [file-origin][file-renamed]

### 19.提交暂存区到仓库的命令  

git commit -m[message]

### 20.直接从工作区提交到仓库的命令  

git commit -a -m[message]

### 21.显示变更信息的命令  

git status

### 22.查看历史信息的命令
git reflog
### 23.Commit的意义是
提交
### 24.pull的意义是
合并分支  有一个仓库，叫Repo A。你如果要往里贡献代码，首先要Fork这个Repo，于是在你的Github账号下有了一个Repo A2,。然后你在这个A2下工作，Commit，push等。然后你希望原始仓库Repo A合并你的工作，你可以在Github上发起一个Pull Request，意思是请求Repo A的所有者从你的A2合并分支。如果被审核通过并正式合并，这样你就为项目A做贡献了
### 25.Push的意义是
推送代码到GitHub上
  将本地代码》GitHub（首先在 github 创建一个代码仓库； 然后本地代码根目录 `git init`，初始化本地代码仓库； 接着添加远程仓库地址： git remote add origin 远程地址然后，执行以下操作即可提交、推送代码了： git commit -a -m "我的第一次提交"git push）



## 第三节课
### 1.MarkDown是什么？
是一个 Web 上使用的文本到HTML的转换工具
是一种轻量级的标记语言。  
它使我们专心于码字，用标记语法，来代替常见的排版方法，可以使普通文本内容有一定的格式  

### 2.MarkDown特点
纯文本内容，兼容所有的文本编辑器和字处理软件  
可以放到版本管理系统中，追踪历史变更  
轻松导入HTML、PDF和本身的.md文件  
简洁、高效、可读、直观、学习成本低  
兼容 HTML  在线观看 平台支持 排版样式简单

### 3.MarkDown用途  
IT人士：写日志、技术文稿、记录代码片段、撰写文档  
科研人员、学生：撰写科技论文、记笔记  
求职者：制作求职简历  
其他：撰写博客  

### 4.MarkDown的编译工具  
Mac OS X:Mou  
Windows：MarkdownPad、MarkPad  
Linux：ReText  
Web：简书、Github、有道云笔记  

### 5.MarkDown的区块元素和区段元素  
区块：段落和换行（两个空格）  
      标题（类Setext形式：用底线的形式表示，=是一级标题，-是二级标题    类Atx形式：# 一级标题   ## 二级标题（有几个#就代表是几级标题 1-6级）)  
      引用   
      列表（有序列表：需要输入1.换行后自动生成   无序列表：-空格 或者 +空格  生成无序列表）  
      代码区块（要简单地缩进 4 个空格或是 1 个制表符）   
      分割线（一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。）  
区段：链接（文字链接：[百度首页](https://www.baidu.com)      URL链接：<https://www.baidu.com>）   
      强调（斜体： *文字*  或   _文字_      加粗： **文字**   或   __文字__）  
      代码 （标记一小段行内代码，你可以用反引号把它包起来     '文字'    ）  
      图片（只能插入在线图片   ![图片名称]（地址））  



