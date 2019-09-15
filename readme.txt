基于odoo13为基础开发新系统
基本操作
git config --global user.name "sanzond"
git conifg --global user.email "sanzond@hotmail.com"
git status
git add -A
git add filename.txt
git commit -m "remark string"
git push origin master -u
git pull
分支
git branch feature3
git checkout feature3
git branch -d feature3
git push origin feature3
git merge feature3
git push :feature3 删除分支
git push feature3:f3 远端别名

合并操作
看日志别名 git log
[alias]
dog = log --all --decorate --oneline --graph
unstage = rest HEAD --
co = checkout
br =branch
ci =commit
st =status

git dog
