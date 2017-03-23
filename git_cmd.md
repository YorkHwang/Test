## GIT命令

1.创建repository

​	mkdir /e/git

​	cd /e/git

​	pwd

​	git init

2.添加文件

​	git add git_cmd.md

​	git commit -m "write git_cmd.mk file"

3.提交文件到本地仓库

​	首先查看配置

​	git config -l

​	git commit -m "write git_cmd.mk file"

4.提交远程仓库

​	添加到远程的git：

​	git remote add origin git@github.com:waltergithub/mygit.git

​	

​	上传到远程的git

​       git push -u origin master	

