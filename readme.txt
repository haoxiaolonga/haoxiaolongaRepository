this is a test;
hello world ;
my Email is haoxiaolonga@gmail.com

初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

第一步，使用命令git add <file>，注意，可反复多次使用，添加多个文件；

第二步，使用命令git commit，完成。

test git add  or git commit  first  git  init   mkdir 路径文件夹  -->git init  pwd -> cd 路径 -> new a txt ->git add txt ->git commit -m"注释"  

--> git add is exists --> git  commit -m“注释”  ==update(pom three)

four : git log (show commit log)    git log --pretty=online (show commit  one online) 

five：HEAD指向当前版本 -->使用命令git reset --hard commit_id(指定回滚到某个提交版本)。 

	git reset hard  head^(前一个版本)	git reset hard HEAD^^(	上两个版本) git reset hard HEAD~100(前100版本) 
	-->用git log可以查看提交历史（回滚）。要重返未来，用git reflog查看命令历史（中间往最新版本跳）。
six:this is a word for test funcction 