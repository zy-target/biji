git提交流程  
git init
git add 复习路线.xmind  
git commit -m "first commit"  
git remote add origin git@github.com:zy-target/biji.git  
git push -u origin master

git checkout -b branch
用rebase合并主干的修改，如果有冲突在此时解决
$ git rebase master

合并工作分支的修改，此时不会产生冲突。
$ git merge work

git push origin dev -u

git status


git commit -a

冲突之后解决完
git add 文件名
git commit -m "备注"

git push
