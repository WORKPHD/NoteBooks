## Git：

- Git是一个开源的分布式版本控制系统，可以记录文件修改历史记录，使用户能够查看历史版本，方便版本切换。
- Git的**本地库**是存放在本地磁盘上。
- 分布式控制系统都是有一个组件——**远程库**，实现代码的统一性

## Git的工作机制：

- **工作区**：代码存放的磁盘的目录的位置；
- **暂存区**：为了让git追踪到工作区的代码文件，将工作区的代码添加到暂存区，暂存区的代码是临时存储的，是可以删除存放在暂存区的文件；
- **本地库**：将暂存区的代码提交到本地库，就会生成历史版本。

![image-20230711202009646](../../TyporaNote/assets/Git/image-20230711202009646.png)

## Git与代码托管中心：

代码托管中心是基于网络服务器的远程代码仓库，简称远程库。

1. 局域网：GitLab
2. 互联网：GitHub、Gitee码云；

## Git的安装：

![image-20230713171820812](../../TyporaNote/assets/Git/image-20230713171820812.png)

![image-20230713172633355](../../TyporaNote/assets/Git/image-20230713172633355.png)

![image-20230713172857498](../../TyporaNote/assets/Git/image-20230713172857498.png)

## Git命令：

```
git --version  //查看版本
git config --global user.name "输入你的用户名"
git config --global user.email "输入你的邮箱"
git init //初始化本地库，使git获取被管理目录的管理权。在被管理的目录下，输入初始化命令，使git知道哪个目录别git管理；
git status //查看本地

git add '文件名'  //将本地文件添加到暂存区
```

### git init命令操作

在被管理的目录下输入初始化命令 ：git init

![image-20230713174748503](../../TyporaNote/assets/Git/image-20230713174748503.png)

git add命令

















