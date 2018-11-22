                      《Java高阶学习笔记》
一、Github学习
    1）常用命令
        -----------常用Bash命令----------
        -> cd: change directory
        -> mkdir: make directory
	-> pwd: print working directory
        -> cp: copy
	-> rm: remove
	-> mv：move
	-----------常用Git命令-----------
	
	git config --list 查看配置信息
	
	git config --global user.name "thomas" 设置用户名称
	
	git config --global user.email "zy2013ecjtu@163.com" 设置邮箱

	-----------Github提交代码相关命令-----
	
	-> git init 初始化一个仓库，产生了如.git文件
	-> git status 查看状态
	-> git add . 检入所有变更文件，还可以指定具体检入文件
	-> git commit -m 【当前变更说明】 提交变更文件到本地仓库
	-> git commit -a -m  同上
	
        -> git remote add origin【别名】 https://github.com/Zy-THOMAS/demo 连接远程仓库
	-> git remote -v 查看
	-> git push origin master 推送代码，需要输入密码
	-> git push -u origin master 
	-> git pull origin master 拉取代码到master分支
	-> git clone https://github.com/Zy-THOMAS/demo 克隆仓库

	
        
