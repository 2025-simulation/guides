
# Table of Contents

1.  [A guide of simulation](#orgf64668c)
2.  [wish list <code>[1/2]</code>](#org97693f8)
3.  [Recommend](#org8687d07)
    1.  [immersive translate](#org444317f)
    2.  [google](#orgba55257)
4.  [Git](#orgb9371e2)
    1.  [wished list <code>[0/4]</code>](#orgcfb9dfa)
    2.  [Configuration](#orgdc51252)
    3.  [Main](#orgc2762e8)
        1.  [clone](#orgfbcdaa1)
        2.  [manage repo](#org7a13673)
5.  [Google](#org7b9e3de)
6.  [Neovim](#orgd8f1b49)
    1.  [简介](#org572aeb3)
    2.  [下载](#org15198bf)
        1.  [Ubuntu](#org7892ad0)
        2.  [windows](#org7b749ff)
    3.  [使用方法](#org9c0be92)
        1.  [打开 neovim](#orgf08c22f)
        2.  [如何使用 Neovim](#org2fbff6d)


<a id="orgf64668c"></a>

# A guide of simulation


<a id="org97693f8"></a>

# wish list <code>[1/2]</code>

-   [ ] git


<a id="org8687d07"></a>

# Recommend


<a id="org444317f"></a>

## immersive translate


<a id="orgba55257"></a>

## google


<a id="orgb9371e2"></a>

# Git


<a id="orgcfb9dfa"></a>

## wished list <code>[0/4]</code>

-   [ ] reset
-   [ ] add
-   [ ] commit
-   [ ] remote


<a id="orgdc51252"></a>

## Configuration

    git config global --global user.name "<username>"
    git config global --global user.email "<email>"


<a id="orgc2762e8"></a>

## Main

program + parameters


<a id="orgfbcdaa1"></a>

### clone

    git clone <repo_path>
    git clone https://github.com/2025-simulation/simple-chat-app.git
    git clone git@github.com:2025-simulation/simple-chat-app.git


<a id="org7a13673"></a>

### manage repo

    git init # initialize the git repo
    git add <the file or folders>
    git commit -m "Message"

The progress

1.  wished list <code>[0/3]</code>

    -   [ ] add graph
    -   [ ] commit graph
    -   [ ] reset graph
    
    ![img](./images/git-local.png)


<a id="org7b9e3de"></a>

# Google

现在我们面临的一些问题都是专业性质比较强的问题，目前中文互联网的可提供的解决方案比较少，于是我们可能绝大部分时间需要在英文互联网寻找解答。

目前英文互联网最好的搜索引擎就是 [google](https://google.com) 。
在一些专业的论坛上通常能够找到最好的答案，比如 [stackoverflow](https://stackoverflow.com/questions) 和 [reddit](https://www.reddit.com/)


<a id="orgd8f1b49"></a>

# Neovim


<a id="org572aeb3"></a>

## 简介

Neovim 是一个终端下的专业的文本编辑器，可以方便地在终端下面直接编辑文本，而不需要退出终端、打开其他软件然后在翻看文件路径找到需要编辑的文件。


<a id="org15198bf"></a>

## 下载

这个是官方的下载地址 [Neovim](https://neovim.io) ，一切以官方的下载地址为准。


<a id="org7892ad0"></a>

### Ubuntu

    sudo apt install neovim


<a id="org7b749ff"></a>

### windows

在官网下载安装安装文件后打开（windows 系统会自动拦截所有类似于可安装程序的文件，不用理会，保留即可），安装之后。在 Windows 的终端下面输入 `nvim` 既可以运行。
tips: 如果不清楚下载的页面的含义，建议自己上网查询，否则不要改动，全部按照默认安装即可。


<a id="org9c0be92"></a>

## 使用方法


<a id="orgf08c22f"></a>

### 打开 neovim

在终端里面输入 `nvim test.md` ，实际就是使用 neovim 创建（如果没有）并且打开一个名为 test 的 markdown 文件。
本质上终端下使用程序就是输入程序名然后跟上一系列的参数。对于文本编辑器实际上使用频率最高的方式就是编辑文件的文件名。
而所有文件的编辑名称分为两个部分：文件名和文件类型。

-   `test.word`: 这就是一个名为 test 的 word 文档。
-   `test.md`: 这是一个 markdown 语法的文档。和 txt 一样属于文本文件，在编程领域尤为常见。


<a id="org2fbff6d"></a>

### 如何使用 Neovim

Neovim 里面有官方自带的教程。
输入 `nvim` 打开 Neovim 之后，不要乱动键盘，确认是英文输入法之后输入 `:Tutor` 然后回车即可查看。注意在输入冒号之后会在左下角出现输入提示，可以查看拼写。
如果阅读英文文档有一些压力，可以选择参考下面的网站 [Neovim Tutor](https://yianwillis.github.io/vimcdoc/doc/usr_toc.html) 。

