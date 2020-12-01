# 用户指南

我们目前借用github, 采用这种大家共同开发的方式，使用Markdown语言组织我们的101项目。我们需要更多的输入！

## 有关github
GitHub是通过Git进行版本控制的软件源代码托管服务平台。

网上有诸多github的教程（诸如https://blog.csdn.net/qq_31001889/article/details/80316503), 大家可以酌情上手（反正闲着也是闲着），借github为窗口了解大家/community里面都在干啥，是一个很不错的选择。这里需要隆重推荐下黄崧的饕餮项目。

在使用Github贡献内容之前，推荐你在自己的设备上安装git命令。
```bash
sudo apt install git ## Debian, Ubuntu etc.

sudo yum install git ## CentOS， Fedora etc.

brew install git     ## MacOS
```
Windows系统可以去git官网下载，或者使用一些包管理器winget, scoop等等来安装（不太熟悉）。


关于我们的Xray-data-101项目，我比较喜欢如下initial的方式：

```bash
git clone https://github.com/PMO-HE/Xray_data_101.git
```

  如果你已经做过initialization，再次更改最好先同步一下，

```bash
git pull
```

然后在你完成编辑后，使用

git commit -m "hhh" //hhh为git commit提交的信息，会显示在你修改的文件的注释里

git push

的方法提交你们的修改——没错，这个文件就是通过如上的方式添加到项目中的。

当然如果能够按照如下网站使用一下分支那就更美好了：

https://www.cnblogs.com/tracylxy/p/6433916.html


当然github还提供图形化客户端，而且部分文本编辑工具也提供GitHub集成，都可以帮助你向我们贡献内容。

## 有关Markdown

Markdown是一种轻量级标记语言，能够让你用简单的格式字符就能完成不错的组织文字的目的,当然它也支持HTML语法。
最重要的是它支持LaTex格式的公式。
[Typora](https://typora.io/)、[Mark Text](https://marktext.app/)是比较推荐的图形化的编辑软件(前者闭源免费，后者开源)。

### Github兼容性
目前发现Github不支持一些Markdown语法，比如TOC目录，TOC目录可以用[gh-md-toc](https://github.com/ekalinin/github-markdown-toc)这个脚本帮助生成。
