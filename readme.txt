Git is a version control system.
Git是一个分布式版本控制系统。
Git is free software.
Git是一款免费的软件。
今日内容：
	1.初始化到Git命令： git init
	2.添加文件到Git仓库：分两步：
		a.使用命令 git add <file> ,可反复多次使用添加多个文件，然后一次性提交；
		b.使用命令 git commit -m <message> ,完成提交。
	3.掌握工作区状态，使用 git status 命令；
	4.如果文件被修改过, git diff 可以查看修改内容.
	
2019-03-23:
1.要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

2.关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

3.此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

分布式版本系统的最大好处之一是在本地工作完全不需要考虑远程库的存在，也就是有没有联网都
可以正常工作，而SVN在没有联网的时候是拒绝干活的！当有网络的时候，再把本地提交推送一下就
完成了同步，真是太方便了！
test!
