# Git基本使用介绍
聂勇｜[nieyong](https://github.com/nieyong)

[2013-1-26] 思开科技研发第一次培训

[2013-6-2] 新员工培训，PPT转化为reveal的slides



## Git简介
* Linus Torvalds
* April 5, 2005   －－ first version／used for Linux version control
* Centralized Version Control   &  Distributed Version Control
* CVS／Subversion  & Git
* Github



## Git工作流程／命令总览
<img src="img-git/git-process.png" width="70%"/>



## Git基本命令讲解
* git add / commit
* git reset
* git checkout
* git branch
* git merge
* git pull / push / rebase
* git config

[参考资料](http://blog.jobbole.com/22647/)



## Git add／commit
<img src="img-git/git-add.png" width="70%"/>

reset命令的完整形式：git reset --mixed HEAD filename

解释：将HEAD版本下的内容覆盖掉stage中的内容，但是不要覆盖working space中的内容；

关于 - -的含义？



## Git reset
<img src="img-git/git-reset.png" width="70%"/>



## Git checkout(1)
<img src="img-git/git-co.png" width="70%"/>

把文件复制到工作空间和暂存区域。
工作空间有unstaged的文件呢？如果暂存区域有没有提交的修改呢？



## Git checkout(2)
<img src="img-git/git-co-2.png" width="70%"/>

切换到分支，同时把索引和工作目录切换到那个分支对应的状态。



## Git  checkout（3）
<img src="img-git/git-co-2.png" width="70%"/>

You are in 'detached HEAD' state.



## Git branch
* git branch				//查看现在所有分支
* git branch hotfix	//新建分支
* git checkout hotfix	//切换到分支hotfix
* git checkout -b 'hotfix' //新建并切换到分支
* git branch -d hotfix	//删除hotfix分支

建议阅读《pro git》的第4节 Git Branching



## Git merge
<img src="img-git/git-merge.png" width="70%"/>

三方合并( three-way merge)



## Git rebase
<img src="img-git/git-rebase.png" width="70%"/>

线性化的自动的 cherry-pick



## Git pull/push
git pull:
git checkout origin/master
git fetch origin
git rebase master
git checkout master
git merge origin/master



## Git config
<img src="img-git/git-config.png" width="70%"/>

* ~/.gitconfig     全局配置
* .git/config       本工程的配置
* .gitignore      	忽略的文件或者路径



## git与项目管理
<img src="img-git/git-project.png" width="70%"/>

[参考资料1](http://www.juvenxu.com/2010/11/28/a-successful-git-branching-model/)
[参考资料2](http://nvie.com/posts/a-successful-git-branching-model/)



## 其它
* Mac下的git命令行[安装程序](http://code.google.com/p/git-osx-installer/downloads/list)
* Mac下的github GUI
* Mac下的git GUI，推荐[Gitx](http://gitx.laullon.com/)
* [Git的设计原则和实现架构](http://www.aosabook.org/en/git.html)
* [推荐博客](http://www.worldhello.net/)
* 推荐的关于github书籍：[《GotGitHub》](http://www.worldhello.net/gotgithub/)
