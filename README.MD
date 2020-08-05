#git cmddemo



Git Process

$ cd gitcmddemo/
$ echo "#git cmddemo" >>README.MD
$ git status
$ dir
$ echo "Now learn Git by CMD" >>test.txt
$ git init
$ git config --global user.email "devesh.kr.srivastava@gmail.com" //get this from git hub
$ git config --global user.name "devesh.kr.srivastava" 
$ dir
$ git add .
$ git commit -m "first commit"
$ git remote add origin1 https://github.com/deveshprojectwork/gitcmdmemo.git
$ git push -u origin1 master

++++++++++++++adding again
$ dir
$ git add .
$ git commit -m "second commit"
$ git push --all

+++++++++++Branches:


$ git branch
* master

$ git branch child1

$ git branch
  child1
* master

$ git checkout child1
Switched to branch 'child1'

$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin1/master'.


