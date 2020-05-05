# git command practice

# 主要的几个区
工作区
暂存区
本地仓库
远程库

# 一些常见命令
工作区 => 暂存区 

`
git add [file][.]
`

暂存区 => 本地仓库

`
git commit -m "something you wanna say"
`

## 版本的回滚

`
git reset --hard [commit id]
`

查看commit id
---

`
git log --oneline

#可以查看所有的commit id

git reflog
`

## 查看差别

`
git diff
`

## 克隆远端仓库

`
git clone [url]
`

## 提交文件给远端仓库

`
git push
`

## 从远端仓库取

`
git pull/fetch
`

## 从工作区丢弃

`
git checkout --file
`

# 分支相关

## 添加分支

`
git switch -c [name]
`

## 列出所在地所有分支

`
git branch -a
`

## 切换分支

`
git switch [name]
`

## 把name分支和当前分支合并

`
git merge [from name]
`

## 删除name分支

`
git branch -d [name]
`







