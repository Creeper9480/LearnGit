## Git安装

------

Git可以在Linux、Unix、Mac和Windows上运行

### 1. 在Linux上安装Git

在以apt（Advanced Packaging Tool）为安装包管理工具的Linux系统上（如Ubuntu、Debian）可以使用如下命令安装Git：

```bash
sudo apt install git
```

稍等片刻，待所有步骤执行完成后，Git便安装完成了。

> 摘自摘自<a href="https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496#0" target="_blank">廖雪峰的官方网站--安装Git</a>
>
> 老一点的Debian或Ubuntu Linux，要把命令改为`sudo apt-get install git-core`，因为以前有个软件也叫GIT（GNU Interactive Tools），结果Git就只能叫`git-core`了。由于Git名气实在太大，后来就把GNU Interactive Tools改成`gnuit`，`git-core`正式改为`git`。

若为其他Linux版本，则可以通过查看<a href="https://git-scm.com/download/linux" target="_blank">Git官网</a>对应的安装方法，然后进行安装。

### 2. 在Mac OS X上安装Git

可以通过homebrew来安装Git，详见<a href="https://brew.sh/index_zh-cn" target="_blank">homebrew官方文档</a>。

### 3.在Windows上安装Git

直接从Git官网<a href="https://git-scm.com/download/win" target="_blank">下载安装程序</a>，然后按安装程序提示进行安装即可。

### 4.安装成功

安装成功后，还可以通过以下命令设置自己的姓名和邮箱（根据自己情况修改）：

```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```

- `git config`命令的`--global`参数，表示这台机器上所有的Git仓库都会使用这个配置，此外，也可以对某个仓库指定不同的用户名和Email地址。