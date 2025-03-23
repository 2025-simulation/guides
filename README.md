
# Table of Contents

1.  [Github Desktop](#orgdae07f1)
2.  [Git](#org1ca5e5b)
    1.  [Configuration](#org13c5707)
    2.  [Main](#org93e4fd8)
        1.  [clone](#orgbaf782c)
        2.  [manage repo](#orga44a1c4)
3.  [Google](#org43c86a6)
4.  [Neovim](#org5c7ec33)
    1.  [简介](#orgea4a3e6)
    2.  [下载](#org032ca82)
        1.  [Ubuntu](#orge4f0b2f)
        2.  [windows](#org7fb0497)
    3.  [使用方法](#orgb4028da)
        1.  [打开 neovim](#org03b011e)
        2.  [如何使用 Neovim](#orgc2562a4)
5.  [Others Docs](#orge7249f1)


<a id="orgdae07f1"></a>

# Github Desktop

If you did not have the experience with command line. You can try github desktop to manage your remote repos.
Seek for help [here](https://www.bilibili.com/video/BV13W411U7HY/?spm_id_from=333.337.search-card.all.click&vd_source=c929e07d3af3e6861de93427e4190229) .


<a id="org1ca5e5b"></a>

# Git


<a id="org13c5707"></a>

## Configuration

    git config global --global user.name "<username>"
    git config global --global user.email "<email>"


<a id="org93e4fd8"></a>

## Main

program + parameters


<a id="orgbaf782c"></a>

### clone

    git clone <repo_path>
    git clone https://github.com/2025-simulation/simple-chat-app.git
    git clone git@github.com:2025-simulation/simple-chat-app.git


<a id="orga44a1c4"></a>

### manage repo

    git init # initialize the git repo
    git add <the file or folders>
    git commit -m "Message"

The progress

1.  wished list

    ![img](./images/git-local.png)

2.  建立远程仓库

    对于如何在 GitHub 建立一个远程仓库，可以参考 [这个文档](https://docs.github.com/zh/get-started/git-basics/managing-remote-repositories) 。


<a id="org43c86a6"></a>

# Google

现在我们面临的一些问题都是专业性质比较强的问题，目前中文互联网的可提供的解决方案比较少，于是我们可能绝大部分时间需要在英文互联网寻找解答。

目前英文互联网最好的搜索引擎就是 [google](https://google.com) 。
在一些专业的论坛上通常能够找到最好的答案，比如 [stackoverflow](https://stackoverflow.com/questions) 和 [reddit](https://www.reddit.com/)

另外如果对于英文阅读有一些压力可以选择在浏览器下载一个插件 [沉浸式翻译](https://immersivetranslate.com/) 。


<a id="org5c7ec33"></a>

# Neovim


<a id="orgea4a3e6"></a>

## 简介

Neovim 是一个终端下的专业的文本编辑器，可以方便地在终端下面直接编辑文本，而不需要退出终端、打开其他软件然后在翻看文件路径找到需要编辑的文件。


<a id="org032ca82"></a>

## 下载

这个是官方的下载地址 [Neovim](https://neovim.io) ，一切以官方的下载地址为准。


<a id="orge4f0b2f"></a>

### Ubuntu

    sudo apt install neovim


<a id="org7fb0497"></a>

### windows

在官网下载安装安装文件后打开（windows 系统会自动拦截所有类似于可安装程序的文件，不用理会，保留即可），安装之后。在 Windows 的终端下面输入 `nvim` 既可以运行。
tips: 如果不清楚下载的页面的含义，建议自己上网查询，否则不要改动，全部按照默认安装即可。


<a id="orgb4028da"></a>

## 使用方法


<a id="org03b011e"></a>

### 打开 neovim

在终端里面输入 `nvim test.md` ，实际就是使用 neovim 创建（如果没有）并且打开一个名为 test 的 markdown 文件。
本质上终端下使用程序就是输入程序名然后跟上一系列的参数。对于文本编辑器实际上使用频率最高的方式就是编辑文件的文件名。
而所有文件的编辑名称分为两个部分：文件名和文件类型。

-   `test.word`: 这就是一个名为 test 的 word 文档。
-   `test.md`: 这是一个 markdown 语法的文档。和 txt 一样属于文本文件，在编程领域尤为常见。


<a id="orgc2562a4"></a>

### 如何使用 Neovim

Neovim 里面有官方自带的教程。
输入 `nvim` 打开 Neovim 之后，不要乱动键盘，确认是英文输入法之后输入 `:Tutor` 然后回车即可查看。注意在输入冒号之后会在左下角出现输入提示，可以查看拼写。
如果阅读英文文档有一些压力，可以选择参考下面的网站 [Neovim Tutor](https://yianwillis.github.io/vimcdoc/doc/usr_toc.html) 。


<a id="orge7249f1"></a>

# Others Docs

1.  [blender-mcp](./docs/blender-mcp.md) needs claude desktop, but it didn&rsquo;t support users in China,
    although with vpn.
2.  [mcp-server](./docs/mcp-server.md)

