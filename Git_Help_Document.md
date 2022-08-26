# Git帮助文档

[Git官网](https://git-scm.com/)

> 什么是Git？<br>
> Git是一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理。

> 为什么使用Git？<br>
> 它可以帮助我们更好的管理自己的代码与版本。

### 一些常用的git指令

```bash
git add 文件名          # 添加文件
git commit -m 名称      # 提交至暂存区
git push origin 分支名  # 推送至远程分支

git checkout 分支名     # 切换至分支
git checkout -b 分支名  # 新建并切换至分支
git branch              # 查看当前选择分支
git diff                # 查看本地改动
git branch -m 旧名 新名 # 对分支进行改名
git status              # 查看当前分支状态

git rm -cached 内容名   # 从提交暂存区删除指定内容
```