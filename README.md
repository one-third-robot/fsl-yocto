### Google Repo Test

### 安装

```bash
git clone https://github.com/one-third-robot/article-007-repo.git
cd article-007-repo
chmod a+x repo
sudo mv repo /bin/
```

这里安装的`repo`的版本是v2.8。

### 使用

```bash
cd ~
mkdir fsl-yocto
cd fsl-yocto
repo init -u https://github.com/one-third-robot/fsl-yocto -b master
repo sync -j4
```

这里我们使用的是`master`分支。如果代码仓库`fsl-yocto`支持其他分支，也可以使用其他分支。

