
## 一些指南

[git下载](https://git-scm.com/downloads)
[git简明指南](https://rogerdudler.github.io/git-guide/index.zh.html)


## git的基本使用

1. 初始化仓库repository
```shell
git init
```
2. 增删文件
```shell
# 增加文件README.md到暂存区
git add README.md
# 增加所有文件到暂存区
git add *

# 从暂存区删除文件README.md
git rm --cached README.md
# 从暂存区删除所有文件
git rm --cached *
```
3. 提交
```shell
git commit -m "对版本的一些说明"
```

