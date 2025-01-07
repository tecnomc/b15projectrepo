# b15projectrepo
This is Playgroud for batch15 champs git practice 


======================================
LINUX :
CLI : 

pwd 
touch filename 
touch file1 file2 file3 

mkdir dir1 
mkdir dir2 dir3 dir4 

clear / ctrl + L 

rm -rf <fname/dirname> 

ls 
ll 
ls -lrth 
ls -la 

===
cd <dir> 
cd ..
========

history
==========================================

DATE: 4 DEC 2024

cat fname 
vi / nano editor 

------------

GIT CONCEPTS:

git init

git config --global user.name kiran

git config --global user.email <email> 

git add <fname>

git status

git commit -m "msg" fname 

------------

git hub account : 

vinay.matangi@gmail.com
vinay.matangi@143

----
git clone <URL> 

cd b15projectrepo

touch madhu 
git add <fname>

git status

git commit -m "msg" fname 


git push 

------------
XXXXXXXXXXghp_UNcRIxyLB52XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

q --> quit

====================
RAMANI :

git clone https://github.com/devopstraininghub/b15projectrepo.git

cd b15projectrepo

touch Ramani 
git add .
git status
git commit -m "Ramani commit" 
git log 
git push 

git pull --rebase

git push 
============================

6 DEC 2024:

BRANCH : 

git branch 
git brnach <br name>
git checkout <br.name> 
--
--
git checkout main/master
git merge <br.name> 

git branch -d <br.name>

git branch -D <br.name>


git push https://github.com/devopstraininghub/b15projectrepo.git <brname>

git push origin <brname>

git push origin -d  <brname>
======================================================================

9 DEC 2024: 

LINUX FILE EDIOR : Vi/vim  edior / nano editor 

VIM/ VI editor:
--

vim madhufile
--------
esc i   --- > insert mode 
....
.... data - xyx 
....


esc :w  (save)

esc :q  (quit) 
or
esc :wq
or
esc :q!
==================================================

git cherry-pick cid 

==================

git conflict 

============
10 dec :

PR (Pull Requests) 


fork - open source project contribution

==============
11 dec 2024:

protecting main branch 

==========

FILTERING:

git log --oneline 
git log --oneline -n 
git log --author kiran
git log --since "12-10-2024"

 
           This option filters the commits to only show those that were made after the specified date
           The date format used here is "MM-DD-YYYY"

========================
git config --list 

========================

Alias
-----
git status  ---> git s 

git config --global alias.s "status"

git config --global alias.s "status"
git config --global alias.s "status"
git s

git log
git config --global alias.l "log"
git l


git log --oneline
git config --global alias.lo "log --oneline"
git lO

======
git config --global --unset alias.ss

==============================

amend
-----
git commit --amend -m "label" -m "label2" -m "label3"

====================================

revert
------
git revert cid

======================================

only for modified files :

git commit -am "messgae"

=======================================


git reset HEAD fname ---> staging to WS 

git reset --soft cid (n-1)  ----> LR to Staging

git reset --mixed cid (n-1) ----> LR to Workspace

===========================================================

DATE: 13 DEC 2024

TAG :

git tag 

git tag <tag.name>
git checkout <tag.name>

git push origin <t.name>

git tag -d <t.name>

git push origin -d  <t.name>

git checkout refs/tags/v1.0

=============================================

git merge  vs git rebase 

git rebase: Reapplies commits from one branch onto another, creating a linear history by rewriting commit history. This makes the history cleaner but alters commit hashes.

git merge: Combines the changes from two branches without altering commit history. It creates a merge commit, preserving the history of both branches.

================================================

git pull --rebase 

======================
git pull vs git fetch 

========================

git pull --> git fetch + git merge origin


git pull --rebase


=========================

git stash list
git stash save "label"

git stash show stash@{x}

POP, APPLY, DROP
-----------------
POP - cut
----
git stash pop


APPLY  - copy
------
git stash apply


DROP  - delete
-----
git stash drop

--------------------------
.git/refs/stash

=========
.gitignore 

log files 


============================

vcs // scm 


Centralized Version Control Systems (CVCS) --> svn 
VS
Distributed Version Control Systems (DVCS) --> git 

============================
git branching strategy in your project ?

REALTIME OPEN SOURCE PROJECT 
-----
upstream 
git fork 
git 
git clean 
=======================


