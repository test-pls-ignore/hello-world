# hello-world
I don't know what I'm doing.

Still trying to figure out what this is.
Looking for Beginner Projects to contribute to.


General Git(hub) workflow:

clone repo to local machine:
 $ git clone https://github.com/user_name/repo_name.git
 
update local master branch:
 $ git pull origin master

create new branch:
 $ git banch branch_name
 
move to branch:
 $ git checkout branch_name
 
add files to branch:
 $ git add .
 
verify status: 
 $ git status
 
commit:
 $ git commit -m "comment"
 
Varian 1)

add branch and files to github repo:
 $ git push -u origin branch_name
 
Pull requests and merging on Github.com
 
swith to local master:
 $ git checkout master
 
delete local branch: 
 $ git branch -d branch_name

 Variant 2)

switch to local master branch:
 $ git checkout master
 
merge with the local master branch:
 $ git merge branch_name -m "comment"
 
add branch and files to github repo:
 $ git push origin master
 
delete local branch: 
 $ git branch -d branch_name


