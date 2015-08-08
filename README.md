# git-apr
A git plugin to apply patches from pull request number.
###Requirement
[hub]  
##Install
1. Install [hub], if you haven't done yet.  
2. Copy git-apr to somewhere where is in $PATH.  
`$ curl -sL https://raw.githubusercontent.com/ryo33/git-apr/master/git-apr > ~/bin/git-apr`  
3. Make git-apr executable.  
`$ chmod u+x ~/bin/git-apr`  

##Usage
```
$ git apr
usage: git apr <pull request number>
```
##Example
Applying patches from #33.  
`$ git apr 33`  
###License
  [License](LICENSE)
###Author
  [ryo33](https://github.com/ryo33/ "ryo33's github page")

[hub]:https://github.com/github/hub
