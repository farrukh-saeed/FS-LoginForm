# FS-LoginForm
ChatGPT Issued the code for the login form 
ChatGPT issued CSS code for style the web page

Bitbucket and Github will be hosting the code

Install git for local repository

Create account either on github or Bitbucket

Verify git version 
$git --version

Cofigure your git on your root folder

$git config --global user.name "Farrukh Saeed"
$git config --global user.email "f@gmai.Compatibl"

verify the file
$cat ~/.gitconfig

It will display the user information 

Adding a SSH key - repo  will have ssh key or zip for downloading

validating your account due to generating ssh key

$ssh-keygen -o

and copy a file path 

/c/Users/Farrukh Saeed/.ssh/id_rsa.pub

then 

$cat /c/Users/Farrukh Saeed/.ssh/id_rsa.pub

Its not working on windows directory but works on ubuntu WSL

All git commands starts with git 

$git clone "paste github url here for downloading"

use first file 

echo "# FS-LoginForm" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main

git remote add origin git@github.com:farrukh-saeed/FS-LoginForm.git

$git remote -v

finally we do push 

git push -u origin main


$git status

$git log


