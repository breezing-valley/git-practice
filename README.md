<**>  代表参数

## 文件操作

> `git status`  查看分支状态

> `git diff <文件名>`  查看文件修改内容(变化差异)

> `git add <文件名>` 提交文件到缓存区

> `git commit -m "<修改说明>"` 提交到当前分支

> `git reflog` 查看历史记录

> `git reset --hard HEAD^` 退回到上个版本

> `git checkout -- <文件名>` 丢弃工作区的修改


## 分支

> `git switch -c <分支名称> = git branch <分支名称>+ git switch <分支名称>` 新建分支并切换

> `git branch` 查看分支，带*号为当前分支

> `git merge <分支名称>`  合并某分支到当前分支

> `git merge --no-ff -m "<合并说明>" <分支名称>` 合并后保留分支合并信息

> `git branch -d <分支名称>` 删除分支
