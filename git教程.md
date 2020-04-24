# git命令行指令

git init：目录初始化命令

git add：添加到工作区

git commit -m 'xxxx'：提交到仓库，可以一次提交多个文件

git status：查看工作区状态

git diff：查看修改内容

git reset --hard commit_id：版本切换，HEAD为当前版本，HEAD^为上一版本，以此类推

git log (--pretty=oneline)：查看提交历史

git reflog：查看历史命令

git checkout -- file：用版本库文件覆盖工作区文件

git reset HEAD ：让暂存区回到工作区

ssh-keygen -t rsa -C "youremail@example.com"：创建密钥对

git remote add origin git@github.com:michaelliao/learngit.git：远程库的关联

git push -u origin master：推送到远程库

git clone：克隆仓库  

git branch：查看分支

git branch ...：创建分支

git checkout/switch：切换分支

git checkout -b /git switch -c：创建并切换分支

git merge：合并分支

git branch -d：删除分支

git log --graph：查看分支合并图

git merge --no-ff -m "merge with no-ff" dev：用普通模式合并

git stash：储存现场

git stash pop/apply：恢复现场

git cherry-pick ID：复制修改

git remote -v：查看远程库

git push origin branch-name：推送分支

git checkout -b branch-name origin/branch-name：本地创建和远程对应的分支

git branch --set-upstream branch-name origin/branch-name：建立本地和远程分支的关联

git rebase：减少分支

git tag （ID）：打标签

git push origin tagname：推送一个标签

git push origin --tags：推送全部标签

git tag -d tagname：删除一个本地标签

git push origin :refs/tags/tagname：删除一个远程标签

.ignore：忽略指定文件

git config --global alias.st status：配置别名

```


```
