### Git

**1.** git add 添加到暂存区
**2.** git commit -m '' 把文件添加到历史管理 
**3.** git log  查看提交日志  
**4.** git log --pretty=oneline 提交日志在一行显示
**5.** git reflog 查看提交日志 id只显示前7位
**6.** git reset --hard HEAD 退回当前版本 HEAD 
**7.** git reset --hard HEAD^ 退回上个版本
       回退多不 git reset --hard HEAD~20 (回退20步)
**8.** git reset --hard ID  退回任意id的版本

**9.** git管理的是修改而不是文件
**10.** 删除文件 git rm  删除后也需要提交
        删除后想恢复 可以通过git reset --hard id 回退

### 创建分支
创建分支 git branch dev 创建一个名为dev的分支
删除分支 git branch -d dev 
切换到   git checkout dev
列出所有分支 git branchg
合并分支 git merge


git checkout -- <file> 丢弃工作区的修改
git reset HEAD file 把已经add到暂存区的文件退回到工作区
