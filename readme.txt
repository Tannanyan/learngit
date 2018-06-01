git init #初始化git仓库 
git add #添加到暂存区域
git commit #提交
git status #查看状态
git diff #查不同
git log #日志
一、  增查删改
			git reset #回退 HEAD^ 回退一个版本 HEAD~10 回退十个版
      git reset --hard HEAD^
      git reset --hard (版本号)
      git reflog #记录每次命令
      git diff    #是工作区(work dict)和暂存区(stage)的比较
			git diff --cached    #是暂存区(stage)和分支(master)的比较
			git checkout -- <file>  #撤销修改，限制不能添加之暂存区
			git checkout #切换分支
			git reset HEAD <file> #可以回退暂存区的修改
			git rm <file> #版本库删除  解决方案： git reset HEAD <file>
			rm <file> #本地删除  解决方案：git checkout -- <file>
二、 github
			ssh-keygen -t rsa -C "youremail@example.com" #创建ssh 
			git remote add origin git@github.com:michaelliao/learngit.git  #关联github
			git push #推送至github
			git 
