git提交流程  
git init
git add 复习路线.xmind  
git commit -m "first commit"  
git remote add origin git@github.com:zy-target/biji.git  
git push -u origin master

git checkout -b branch
用rebase合并主干的修改，如果有冲突在此时解决
$ git rebase master