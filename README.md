# Suggestions_for_beginner
给本科实验室的同学的一些小技巧
### 关于怎么研究一个方向的：

0.可以先直接搜索一下相关博客等了解一下这个方向是干什么的，前景和意义，有个大概的定位和了解

1.1搜寻相关的综述，可以先看简单的博客综述总结，或者知乎专栏，主要了解方向的：起源，传统方法，深度学习方法，以及现在常用的方法和进展，了解现在能做的最好方法思路的performance以及瓶颈在哪里(了解坑的方向以及坑的深浅)，通常各种会议或者论坛也会有相关报告，可以直接B站搜相关方向的视频

1.2在前面基础的了解下，可以看论文的survey，通常survey里面方法比较详细，比博客要好，能够更好的了解方向的整个发展

2.去找方向里面的milestones，通常survey里面也会列出时间线和相关重要的里程碑的论文，可以细看里程碑式论文的方法，通常是一种新方法或者新思路新框架的出现，通常会引起一波潮流，是后面一阵论文的基础

3.了解方向最新的动态，最新的顶会CVPR，ECCV等上面的相关论文，是不是基于前面里程碑论文的改进，还是新的思路，同时关注最新的论文的performance和瓶颈

TIPS：

1.读论文或者看综述的时候，注意一下团队和作者，一方面对大佬心生膜拜，另一方面擅长相关方向的团队，可能后续也有有一系列前沿的工作，可以持续关注，此外以后也可能有机会过去学习也不一定；

2.组会可能会有很多其他方向的，比如CV，可能有做细粒度的，有检测分割，可能开组会的汇报不是你的研究方向，虽然可能不怎么听得懂，但是多听绝对是会有好处的，经常会有一些想法或者方法可以借鉴，哪怕是attention也是从跨域的NLP借鉴过来的

### 代码方面

1.github代码下载不下来，可以去国内的码云，然后导入github的项目，然后码云下载就很快；

2.跑代码一定要有checkpoints及时的存模型，最好也得有try&catch，方便及时打断运行时保存模型，log也要写好，尤其注意(时间，epoch，acc等)

### 服务器方面

1.ssh tangtao@210.20.96.136                       ssh  用户名@服务器IP   

然后输入密码就可以

2.服务器IP应该是只有校园网才能连，远程得先有VPN

3.本地与服务器之间文件和代码的上传和下载

文件的话，scp命令即可，要是习惯桌面，windows上推荐软件winscp，mac上推荐Cyberduck，传输协议SFTP；代码的话，可以当做文件处理，本地改好再传，要是觉得不方便，可以利用pycharm专业版连接服务器，直接联通本地和服务器；

4.shell

mac和ubuntu就原生的shell的就非常棒了；windows上其实winscp也有，个人推荐windows上用ubuntu for windows，在windows应用商店下载就行，或者其他的软件类似xshell

### 组会、报告、周报等方面

PPT或者报告，如果是引用的别人的工作，PPT当页，或者报告的最后，一定给出链接和作者；
### 其他

和师兄师姐老师们搞好关系，多动手实验，不懂就多问，不用不好意思

