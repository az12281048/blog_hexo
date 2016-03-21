---
title: windows下搭建cuda开发环境
date: 2016-03-18 09:43:05
tags:
---
## 我的配置信息
windows 8.1 64位系统
独立显卡 Gefore GT540M(Gefore系列的显卡都支持CUDA编程)

## 安装步骤
### 1 安装英伟达官方的显卡驱动。
  Gefore显卡驱动下载地址：http://www.geforce.cn/drivers

### 2 安装CUDA ToolKit
  下载地址：https://developer.nvidia.com/cuda-downloads

### 3 安装visual studio
  我用的是visual studio 2010。
  装上之后，打开visual studio，点击 文件->新建->项目，可以看到已安装模板中NVIDIA下面有CUDA的选项。选择该模板，输入项目名称，然后选择项目文件夹保存的位置，点击确定。新建项目完成。
  新建完项目之后，可以看到自动自动生成了一个kernel.cu文件。这是一个可以运行的CUDA程序例子，可以参考。
  
