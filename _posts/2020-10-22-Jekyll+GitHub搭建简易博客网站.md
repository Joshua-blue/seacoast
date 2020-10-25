---
layout: post
title:  "Jekyll+GitHub搭建简易个人博客网站"
author: joshua
categories: [ Blog ]
tags: [ Jekyll ]
image: assets/images/blog.jpg
beforetoc: "Jekyll+GitHub搭建个博客-开始搭建"
rating: 5.0
toc: true
---



# 一、搭建环境

使用以下指令逐一查看开发环境，缺少自行安装：

```sh
ruby -v
gem -v
gcc -v
g++ -v
make -v
git --version
```

![image-20201019105907956](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019105907956.png)

![image-20201019110003433](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019110003433.png)

# 二、创建仓库

仓库名：equinox-flower

仓库描述：Equinox flower, open on the other side, flowers do not see leaves, leaves no flowers.

![image-20201019080726491](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019080726491.png)



![image-20201019081133078](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019081133078.png)

![image-20201019081641396](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019081641396.png)

搭建Git简易网站：

![image-20201019081913531](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019081913531.png)

选择喜欢的模板：

![image-20201019082658457](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019082658457.png)

![image-20201019082746334](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019082746334.png)

![image-20201019082855274](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019082855274.png)

![image-20201019082913050](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019082913050.png)



# 三、下载模板

http://jekyllthemes.org/

![image-20201019083053829](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083053829.png)

![image-20201019083202575](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083202575.png)

解压到桌面：

![image-20201019083230852](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083230852.png)

![image-20201019083347210](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083347210.png)

![image-20201019083435833](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083435833.png)



# 四、开始搭建

## 4.1、克隆仓库

把GitHub上的仓库克隆到本地。

复制HTTPS链接：

![image-20201019083758532](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083758532.png)



打开终端进行操作：

![image-20201019083951247](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019083951247.png)

## 4.2、修改仓库

修改本地仓库内容。

将模板里所有文件复制到本地仓库中：

![image-20201019084420512](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019084420512.png)

![image-20201019084451872](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019084451872.png)

![image-20201019084526244](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019084526244.png)



## 4.3、上传仓库

将修改后的本地仓库内容上传到远程仓库。

打开终端进入仓库目录操作：

![image-20201019085006492](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085006492.png)

![image-20201019085020630](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085020630.png)

刷新远程仓库：

![image-20201019085135171](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085135171.png)

访问网站地址：![image-20201019085247947](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085247947.png)

![image-20201019085339612](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085339612.png)

可能需要开启网站代理服务：

![image-20201019111530555](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019111530555.png)

![image-20201019111548130](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019111548130.png)





![image-20201019085404589](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085404589.png)

## 4.4、修改路径

解决网站未加载样式问题。

修改资源路径：

![image-20201019085717174](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085717174.png)

![image-20201019085627052](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085627052.png)

尝试修改路径：

![image-20201019085854605](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085854605.png)

预览修改效果：

![image-20201019085939293](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019085939293.png)

修改config.yml文件：

![image-20201019093917163](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019093917163.png)

![image-20201019094030423](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019094030423.png)

再次提交：

![image-20201019101558624](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019101558624.png)



稍作休息后多次刷新页面：

![image-20201019090908756](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019090908756.png)

![image-20201019091228466](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019091228466.png)

## 4.5、流量统计

使用 [百度统计](https://tongji.baidu.com/web/welcome/login)  进行网站访问流量统计。

![image-20201019091632951](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019091632951.png)

![image-20201019091810116](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019091810116.png)

复制代码到 head.html 文件头部：

![image-20201019091900061](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019091900061.png)

![image-20201019092815646](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019092815646.png)

![image-20201019092851397](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019092851397.png)

再次提交：

![image-20201019101935259](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019101935259.png)

查看效果：

![image-20201019102122380](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019102122380.png)

![image-20201019103943267](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201019103943267.png)

## 4.6、完善网站

根据自身需求，修改配置文件，配置专属网站。

![image-20201025222248759](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201025222248759.png)



![image-20201025222355075](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201025222355075.png)

![image-20201025222432322](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201025222432322.png)

![image-20201025222520388](https://raw.githubusercontent.com/Joshua-blue/seacoast/gh-pages/assets/images/blog-img/image-20201025222520388.png)