git相关命令
===========

# 代码提交流程

```shell
// 查看文件状态，是否有改动
git status

// 查看文件差异
git diff readme.txt

// 添加修改
git add readme.txt

// 提交修改到仓库
git commit -m "add readme.txt"

// 提交修改到分支
git push mybranch

// 查看分支
git branch -a

// 切换分支，更新主分支内容到分支
git checkout mybranch
git merge master

// 创建修改分支，之后合并分支到主分支
git chechout -b mybranch
git add ***
git commit -m "***"
git checkout master
git merge mybranch
git push origin
git branch -d mybranch
```

# 版本查看

```shell
git log
```
