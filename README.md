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
git reset [commit id]
`

查看commit id
---

`
git log --oneline
#可以查看所有的commit id
git reflog
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




