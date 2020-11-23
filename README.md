# File storage

For temporary storage.

## use git

``` git
git clone git@github.com:hex0x7c/storage.git mygit
```

**提交修改**

- `git add .` 添加文件，点号为所有文件
- `git status` 查看仓库当前状态，显示有变更的文件
- `git diff` 比较文件不同，暂存区和工作区差异
- `git commit` 提交暂存区到本地仓库
- `git rm` 删除工作区文件
- `git mv` 移动或重命名工作区文件

**提交日志**

- `git log` 查看历史提交记录
- `git blame <file>` 以列表形式查看指定文件的历史修改记录

**远程操作**

- `git remote` 远程仓库操作
- `git fetch orgin master` 从远程获取代码库,从orgin远程，拉取master的分支到本地分支orgin/master，自然需要同时指明袁成明和分支名
- `git merge origin/master` 合并名为origin/master的分支到当前分支，分支合并与远程无关，需指定被合并的分支
- `git pull orgin/master` 下载远程代码并合并，
- `git push origin master` 上传远程代码并合并，推送本地master到远程origin
