# GitHub 
###### ( 1 )



## Abstract
 1. Get [GitHub](http://www.github.com/) User ID
 2. Get [GitHub for Windows](http://windows.github.com/)
 3. New Repository
 4. Commit
 5. Reset
 6. Push
 7. Pull
 8. Reference



## Get GitHub User ID
 [GitHub](http://www.github.com/)



## Get GitHub for Windows
 [GitHub for Windows](http://windows.github.com/)



## New Repository
 create A repo `[Local]`

 		$ git init



## Commit
 add file `[Local]`

  		$ git add .

 commit `[Local]`

  		$ git commit -a -m '[Commit]' 



## Reset
 reset HEAD to a previous commit `[Local]`

 		$ git reset --hard HEAD~1

 reset HEAD to top `[Local]`

 		$ git reset --hard HEAD~#



## Push
 adding a remote `[GitHub]`

 		$ git remote add origin https://github.com/[GitHubID]/[Repo].git

 push the repo `[Local->GitHub]`

 		$ git push -u origin master




## Pull
 clone a repo `[GitHub->Local]`

		git clone https://github.com/[GitHubID]/[Repo].git
 
 pull the repo `[GitHub->Local]`

 		git pull origin master



## Reference
 1. [GitHub Help](https://help.github.com/‎)
 2. [Will 保哥的技術交流中心](http://blog.miniasp.com/post/2013/08/19/Learning-Git-Part-1-Installation-Options-Tool-Usage-on-Local.aspx)
 3. [Tsung's Blog](http://blog.longwin.com.tw/2009/05/git-learn-initial-command-2009/)