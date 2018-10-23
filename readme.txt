.git 版本库
git add 文件名             添加，将文件修改添加到暂存区
git rm  文件名             删除文件
git commit -m ""           提交，将暂存区所有内容提交到当前分支

时光穿梭：
git log                    查看提交历史，以确定回退版本
git log --pretty=oneline   历史版本显示为一行
git reflog                 查看命令历史，以便确定要到未来版本

HEAD                       表示当前版本
git reset --hard 版本号    进入到某一版本

git与其他版本控制系统区别： 有暂存区概念

.git                        不属于工作区，是git的版本库   


git status                  查看状态
git diff  文件名            查看变化
git checkout -- 文件名      1.修改后还未放到暂存区，撤销修改回到和版本库一样
		            2.已添加暂存区，又作了修改，撤销到添加暂存区后的状态

git reset HEAD 文件名       暂存区的修改撤销，重新放回工作区


git remote add origin git@github.com:yourname/learn.git
			    添加远程仓库	
			 			
git push -u master origin   内容推送到远程，第一次提交需加 -u
git clone                   克隆远程仓库  

------------------------------------------------
分支管理：


git branch                  查看所有分支
git branch  dev             创建dev分支
git branch -d  dev          删除dev分支
git checkout dev            切换到dev分支 

git checkout -b dev         创建并切换到dev分支

git merge  dev              快速合并指定分支到当前分支上

git log --graph             看到分支合图
Q按键                       退出log查看

git merge --no-ff   dev     普通模式合并，合并后历史有分支

git stash                   把工作隐藏下，修复bug
git stash  pop              回到工作现场

git branch -D dev           强行删除一个没有合并的分支
 
git remote -v               显示远程库的信息
			    显示抓取和推送的地址
git push origin dev         把该分支的提交推送到远程


git branch  --set-upstream branch-name  origin/branch-name 
			    将本地分支与远程分支建立联系 
git pull                    拉取远程分支

						
		
标签管理：
git tag  v1.0   commit_id   给之前版本打标签
git tag  v1.0               打标签
git tag                     查看所有标签
git tag -a "标签名" -m "说明文字" 

git tag -d  "标签名"        删除本地标签
git push origin :refs/tags/<tagname> 
			    删除远程标签
git push origin  标签名     将标签推送到远程   
git push origin  --tag      将全部标签推送到远程   


自定义git：
git bash 打开 ，输入touch .gitignore 创建忽略文件

