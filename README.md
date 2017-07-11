# HandBook
Recollect your git and npm commands.
<br>
##<img src="https://img.shields.io/badge/git----blue.svg?style=flat-square"> :
- <code> $ git --version </code>                                           //To check version of git

- <code> $ git config --global user.name "<Your Name>"</code>              //To set Name(NOT USERNAME)

- <code> $ git config --global user.email "<youremail@example.com>"</code> //To set email

- <code> $ mkdir <FOLDERNAME><br>$ cd <FOLDERNAME></code> //To make a new directory and navigate to that directory

- <code> $ git init</code> //Turn Git on for a folder

- Make a new readme.txt file save it to the same folder<br>

- <code> $ git add readme.txt <br> $ git commit -m "<your commit message>"</code> //add file and commit your changes to local directory   
- <code> $ git diff </code> //Difference between your current and last commit

- <code> $ git status</code> //to check status of your previous commits

- <code> $ git config --global user.username <USerNamE></code> //To set your Username make sure it is same as your github username

- <code> $ git remote add origin <URLFROMGITHUB></code>   //Your local repository now knows where your remote one named 'origin' lives 
on GitHub's servers.                                                         

- <code> $ git clone <URLFROMGITHUB></code> //Clone any repository from github to your local make sure you are not in another git repo 
folder         

- <code> $ git remote add <REMOTENAME> <URL></code> //Pull the changes in original repository to your clone or fork with a remote name

- <code> $ git remote -v</code> // to view remote connection

- <code> $ git status</code> //to check in which branch are you

- <code> $ git branch <BRANCHNAME></code> //Create a branch

- <code> $ git checkout <BRANCHNAME></code> //Go to that branch

- <code> $ git add <NameOfAnyNewFileAdded> </code>
// Add and commit to your branch in local
- <code>$ git commit -m "<commit message>" </code>
 // Add and commit to your branch in local

- <code> $ git push origin <BRANCHNAME></code> //Push your branch to github repository

- <code> $ git pull <REMOTENAME> <BRANCHNAME></code> //Pull any changes to your repository by any other collaborator

- <code> $ git merge <BRANCHNAME></code> //merge changes in your branch to master locally

- <code> $ git branch -d <BRANCHNAME></code> //delete branch from local

- <code> $ git push <REMOTENAME> --delete <BRANCHNAME></code> //delete your branch from github by remote name(line 30)

- <code> $ git pull <REMOTENAME> <BRANCHNAME></code> //pull from github via a remote name
