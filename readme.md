# 创建仓库

* 1:Git本地仓库创建(http://www.cnblogs.com/zhongxinWang/p/4205339.html)
新建文件夹
Git bash进入
git init创建

* 2：查看状态
git status： (use "git add" to track) WorkSpace的状态
"git add test.txt：git status：stage的状态
“git commit -m”来提交更新了

* 3:提交
-m后面跟的是对commit的描述（message）。
git commit -m "add test0.txt into Marvel"

* 4:显示差异
git diff

* 5：暂存区
git add .则无差异

* 6:撤销
..

* 7：本地的仓库传到github
[本地的仓库传到github配置ssh key](http://blog.csdn.net/llf369477769/article/details/51917557)

* 8:first commit
git remote add origin git@github.com:SherlockConstine/mygit.git


注：
**address要公开**
首次提交，先git pull下，修改完代码后，使用git status可以查看文件的差别，使用git add 添加要commit的文件。

* 9:掉线问题 
[GitHub教程--上传项目四步法](http://www.cnblogs.com/JEckDe/p/5134693.html)
git remote add origin git@github.com:yourName/yourRepo.git
有时候输入这个语句的时候，github可能会"掉线"。会报fatal: remote origin already exists.这个错误。这时只需要输入
git remote rm origin 再输入上面的代码就可以了

* 10:挂github
git push -u origin master

