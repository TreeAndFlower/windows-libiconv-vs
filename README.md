#windows下用VisualStudio编译libiconv库

##背景

由于在linux下使用libiconv库进行gbk32与utf-8转码，在移植到windows平台的时候，发现系统里是没有libiconv库，所以从网上找了一些资源和教程，最终发现了一个很给力的解决办法，因此来记录一下备份一下

##解决方案

https://www.codeproject.com/Articles/302012/How-to-Build-libiconv-with-Microsoft-Visual-Studio

该链接libiconv的版本：1.14版本
这个链接给出的解决方案很给力，大神给出了详细的修改源码的过程

##声明
在windows下用VisualStudio编译libiconv库；
本项目来自于PARK Youngho在CodeProject上面贡献的答案，上传上来备份一下答案（项目源码来源于https://www.codeproject.com/Articles/302012/How-to-Build-libiconv-with-Microsoft-Visual-Studio）
该项目使用的libiconv版本为1.14版本，亲测用vs2015编译出的库可生效；

