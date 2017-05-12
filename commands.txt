
## Table of Contents 


*[Tutorial Basic Commands: add, commit, push](#Tutorial Basic Commands: add, commit, push)

*[Tutorial Basic Commands: add, commit, push](##Tutorial Basic Commands: add, commit, push)

#Tutorial Basic Commands: add, commit, push
-------------------------------------------
You dont have any changes
$ git status 
$ git add filename.py //  add file to staging area 

Add chenges to local version control version control DB. You still not pushed these changes to remote server 
$ git commit //
$ git log 
Now am ready to push git code 
$ git push  // It pushes the code to remote server .. go and check in the cloud 

// You will run 'git status' a lot   
// next if you did any changes to the code ; run 'status' cmd  ; there modified file is displayed in green 
// to check the differences bw "local changes" and "previous version" of the file use cmd 'git difftool'
$ git difftool HEAD   // here i setup meld as my difftool 
$ git commit -m 'add some comment based on your changes'
$ git push

Undoing/Reverting/Resetting code changes
-----------------------------------------
clone github repo

$git clone https://github.com/VamsiKavety/python_essential.git  // Clone means it download the repo to your computer 
or
$git clone git@github.com:VamsiKavety/python_essential.git

step : How to Undoing your Uncomitted changes 
$ git status 
$ git checkout --<file name.ext> to discart changes in working directory 


What if you have multiple file changes ?
$ git checkout -- .  // '.' will undo changes made to all the files in the working directory 
step : How to Undoing your Comitted changes 


$git revert 







