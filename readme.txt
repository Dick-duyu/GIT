Git is a version control system.
Git is free software.
Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.


git init		//将当前目录变成Git可以管理的仓库
git add 文件名		//把文件添加到仓库
git commit -m "备注"	//把文件提交到仓库
git log			//显示从最近到最远的提交日志
git reset --hard HEAD^	//回退到上一个版本，HEAD^^上上一个版本，HEAD~100上100个版本
git reset --hard HEAD值	//指定回到某个版本
git reflog		//查看输入记录
git diff HEAD -- 文件名	//命令可以查看工作区和版本库里面最新版本的区别
git checkout -- 文件名	//可以丢弃工作区的修改，让这个文件回到最近一次git commit或git add时的状态。
git reset HEAD 文件名	//可以把暂存区的修改撤销掉（unstage），重新放回工作区
git rm 文件名		//于删除一个文件并git commit -m "备注"
