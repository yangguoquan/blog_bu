title:git 学习笔记
date: 2016-04-15 21:45:29
tag: ['git','github']
---

### git 安装
[git官网][1]  
去官网下载最新的git安装包，按照步骤安装即可。
> windows下方便使用的话，可以将 **git bash here**  和  **git GUI here** 打勾
这样鼠标右键菜单栏会自动将这两个工具集成

### git 工具
[sourcetree][2]
很方便的一个git可视化版本管理工具。界面很清爽直观。对于不擅长git指令的小白还是很容易上手的。
windows和mac平台都支持。
[github][3]仓库。没有一个程序猿不知道它把。

### git 指令

1. ###基本操作
> * git init   ———— 初始化仓库
  * git status ———— 查看仓库状态
  * git add 文件名 ———— 向暂存区中添加文件
  * git commit ———— 保存仓库的历史记录
    * git commit -m "提交信息"
    * git commit 自动启动编辑器记录提交信息
    >>  第一行：用一行文字简述提交的更改内容  
        第二行：空行  
        第三行以后：记述更改的原因和详细内容  
    * 中止提交：提交信息留空并直接关闭编辑器
  * git log ———— 查看提交日志
    * git log --pretty=short  只显示提交信息的第一行
    * git log 目录/文件名 只显示指定目录、文件的日志
    * git log -p 文件名 显示文件的改动
  * git diff ———— 查看更改前后的差别














[1](https://git-scm.com/)
[2](https://www.sourcetreeapp.com)
[3](https://github.com/)