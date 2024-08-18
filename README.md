Git commnds:
1.To convert empty folder to git repo:
... git init

2.Move file from unstaged to staged
single/specific file
a)git add fileName

b)Muliples files

git add file1 file2

3.All files

git add . 
git add -all


3.Move file from staged to unstaged
a)single/specific file

git reset fileName1

b)mutiple files

git reset fileName1 fileName2

c)all
git reset

to move files from commit area to staged area

git reset --soft head~1

to move files from commit area to unstaged area and delete the files in the commit permennetly

git reset --hard head~1



create a new repository on the command line:
echo "# Git_Practice1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/chanduujjina-java/Git_Practice1.git
git push -u origin main

push an existing repository from the command line:
git remote add origin https://github.com/chanduujjina-java/Git_Practice1.git
git branch -M main
git push -u origin main


create a new branch and switched to the same in local repository:
git checkout -b branchName

switching from one branch to anothe branch
git checkout branchName
