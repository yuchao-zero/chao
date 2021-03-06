# **Git**

## 什么是版本控制？
现在有这样的一个场景：我们在写论文的时候，写完了提交给指导老师去审核，老师说你哪哪哪写的不好要改改，于是乎，你就屁颠屁颠的去改。一般的做法是：<font color=red>不直接在原论文上修改，而是复制一份，在新复制的那一份上做改动。</font>因为如果改了论文，被老师评价说还不如上一次，让你重改，你还可以找到上一次的论文，但是如果不复制，直接在原来的论文上改动。  
在上面的场景中，原论文就是一个版本，新复制的论文又是一个新的版本。<font color=red>简单点说，我们复制原论文，产生新论文的这个过程就叫版本控制。</font>只不过这个版本控制是我们手动完成的。 

## 什么是版本控制系统？
**版本控制系统**就是自动帮我们完成上面操作的系统或者说就是一个应用程序（这里的系统不是指操作系统，而是一个应用系统，就是一个程序）

## 版本控制系统如何帮我们控制版本？
我们需要进行版本控制的文件都要提交到一个**仓库>其实就是一个隐藏文件夹**里面，我们对文件做出的修改都会被这个版本控制系统侦测到，如果我们要保留这个版本的文件，就要通过版本控制系统提供的命令把文件提交到仓库里面，然后版本控制系统就会自动为我们提交的文件打上版本号。

## 仓库分几种
1. 本地仓库：建立在本地的文件夹。
2. 远程仓库：建立在互联网的服务器内的文件夹。

## 版本控制系统分为几种
1. 分布式版本控制系统   
- 配有上述两个仓库，在你的电脑上有一个本地仓库，在远程的服务器上有一个远程仓库。
- 我们在提交文件的时候会先提交到本地仓库，然后在有网络的情况下，再从本地仓库提交到网络上的远程仓库。
- Git 就是一个典型的分布式版本控制系统
2. 集中式版本控制系统
- 配有上述的远程仓库，当然如果你的这台电脑就充当远程服务器的角色，那远程仓库其实就在你这台电脑上。
- 我们在提交文件的时候是直接提交到远程仓库。
- SVN 就是一个典型的集中式版本控制系统

## 什么是Git
就是一个帮我们管理文件版本的程序，专业名称叫：分布式版本控制系统 

## 什么是github
github是一家提供公有git服务的公司。github担任着远程仓库的角色，就是一个存放在外网服务器上的一个文件夹。   
远程仓库除了github外，还有gitee（码云）。

————————————————
版权声明：本文主要来自CSDN博主「曲健磊」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/a909301740/article/details/81636662