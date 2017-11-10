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
six: this is a word for test funcction   git status 显示暂存区状态  git add （make file move to 暂存区） git commit (暂存区到分支)

seven :now this is test ，now this is  a  other test，git this aaaaa test(git add 修改后需要再git add 提交时从add 到的暂存区提交的，而不是当前工作区)
·
··	git diff head -- <filename> 用git diff HEAD -- readme.txt命令可以查看工作区和版本库里面最新版本的区别

eight : git checkout -- readme.txt获取最近一次add或者commit时的版本，
		（git reset head filename 讲其从暂存区提出，回到工作区，再用git checkout -- filename回到最初）
		（如果是已经提交到库git reset --hard commit_id 回滚到某个版本 ）

nine :rm filename 删除工作区文件 git rm filename 删除文件提交至暂存区 git commit -m"提交至仓库"

ten: 	git 要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

		关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

		此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
 
eleven:  git checkout -b newgit(分支名字)=git branch newgit +git checkout newgit
			git branch  --显示所有分支   git merge newgit (合并分支到当前分支)
			git branch -d  newgit (删除分支)		
			
twelve： deal merge this is one(合并后)   git log --graph 显示分支合并图 git add -- git commit -- git merge 分支  (合并分支到当前)
 
