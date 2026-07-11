# Learning Git

This repository contains the basics of Git and GitHub.

It also serves as a playground where I test Git commands and features while learning.

<h1>Basics</h1>

You can use simple HTML tags inside a `README.md` file.

The heading above is created using an HTML tag.

When we open git we are in the root directory by default.

Keep in mind that i have chosen git default termial as vs codes termial so maybe things may be different for you.

<h2> Git config</h2>

1. `git config` --global user.name "Myname"' - add your username in gits config file.
2. `git config` --global user.email "Myemail"'- add your email in gits config file.
3. `git config` --list'- shows the gits config file.

# Git basic Commands

1. `ls` — Shows all files and folders in the current directory.
2. `cd <folder-name>` — Moves into the specified folder.
3. `cd ..` — Moves back to the parent directory.
4. `pwd` — Displays the current working directory.
5. `git clone <http>` -Clones the repo on your local machine(laptop/pc).
6. `ls -a` -Shows the hiddin files (make sure to open to repo by cd after cloneing it).
7. `git status`-Shows the branch you are on and some important informations which i have told in basic points.
8. `git add <filename>` -adds new or changed files in gits staging area.
9. `git commit <filename> "comment"` - records the change before pushing it
10. `git push origin main` - pushes your committed file to the git repo and updates the repo
11.`git init` - makes your normal folder a git repo (for more info scroll down)

<h2>Basic Points</h2>
<h3>Git clone</h3>
You can try to clone this repo by using this http link https://github.com/utkarshsinghal28/Learning-git.git 
or you can try to clone your own repo.<br>
Keep in mind this will clone the repo in the folder you run this command on by opening your termial there.
<h3>Git status</h3>
while using git status it will either tell you there is nothing to commit if no changes.<br>
If you make a change the termial will tell you no changes added to commit.
<h4>File types</h4>
<h5>untracked</h5>
If you create a file inside the folder you are using it will say its an untracked file.<br>
<h5>modified</h5>
If you change the file contant in a file which is already commited.
<h5>staged</h5>
A file ready to be committed(file is added).
<h5>unmodified</h5>
the orginal repo you cloned without any changes or if you commit the staged file(added file is committed).
<h3>Git add</h3>
You can also add multiple files by using git add . and it update the file and makes them ready to be committed.
<h3>Git commit</h3>
You can do git commit -m "comment" to commit multiple files at onces.
<h3>Git push</h3>
you can push your git file into your git repo by using git push origin main.(here your code is being pushed to the branch main)
<h3>Important point</h3>
You need to change your termial in vs code from powershell to bash trust me it gives a lot of problems
if you dont.<br>

# Git init

Suppose you have a new folder in which you have code or you have made a project and want to upload to git than we use the following order:<br>
 Git init-->git add .-->git commit -m "any comment"-->`than create a repo in github without readme if you dont have it in your project after this step we will link them for that`<br>git remote add origin<--link to that repo--> --->git remote -v //verify the repo --> git branch // checks the branch<br> git push origin main(at last you push it normally by this command)
<br>

 git branch -M main //changes the name like we changed the name to main now

# Git branches
1. `git branch`-->lists all the branch
2. `git checkout -b createnew`--> creates a new branch
3. `git checkout name`--> we switch to that brach
4. `git branch -d createnew`--> deletes the branch
<br>

`Note` -->suppose you are working on main and create a branch new main and add more features on it than those features wont be shown on main until you merge them

<h2>Merging</h2>