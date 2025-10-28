+++
date = '2025-09-22T10:53:52+08:00'
draft = true
title = '利用GithubPages搭配Hugo的blowfish主题搭建个人博客'
+++

# 利用GithubPages搭配Hugo的blowfish主题搭建个人博客
&emsp;&emsp;偶然在小红书上刷到一个博主想要搭建一个个人博客网站，于是我也动了心思，最开始的选择是WordPress，但是要钱。<br>
&emsp;&emsp;花钱？不可能的。<br>
&emsp;&emsp;于是选择了Github Page，主要有两个优点很吸引我。
- 免费
- 安全

&emsp;&emsp;但是在实际的部署过程中遇到了不少问题，在这里记录一下。

## 准备工作
1. github的准备
   1. github账号
   2. github page的博客仓库
   3. 更改权限
2. 本地电脑
   1. git
   2. hugo
   3. vscode

## 1. github准备
### 1.1 github账号注册
#### 1.1.1 登录网站
https://www.github.com

#### 1.1.2 注册账号
选择sign up按钮，填写账号信息，用户名后面在创建仓库的时候会用到，建议想个好一点的（当然了，有多余的预算也可以买域名替换，但是我没有，所以建议大家去看别的文章）。

### 1.2 创建博客所需的仓库
点击按钮，仓库名的格式一定是username.github.io，这样github才能识别到。

### 1.3 修改权限
创建好仓库以后，点开仓库，然后点击setting，在左侧选择Actions，点击里面的General，将右边的Workflow permissions中改为Read and write permissions。

## 2. 本地电脑
### 2.1 安装git
由于作者用的是Windows，所以本文只描述Win11版本的安装过程，不过各个平台都差不多。
### 2.2 安装hugo

### 2.3 安装vscode

## 3. 配置博客网站

## 4. 写博客