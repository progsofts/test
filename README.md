# test

怎么样更新token

填写用户名和邮件地址
git config --global user.name "progsofts"
git config --global user.email "119218528+progsofts@users.noreply.github.com"

如果有需要提交的代码，先提交。之后再执行如下代码
以下命令假定当前分支名为: main

git remote -v
git remote rm origin
git remote add origin https://ghp_WMSvSxxxxfgghrtyt@github.com/progsofts/test.git
git push --set-upstream origin main

如果遇到push冲突，先调用
git branch --set-upstream-to=origin/main
然后再调用
git pull --rebase
之后再调用
git push --set-upstream origin main



测试新电脑配置，用户名和邮箱，新token

add new line.

add second line.

