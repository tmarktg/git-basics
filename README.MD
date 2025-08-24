What is git?

- open source version control system

What is version control?

- management of changes to documents, computer programs, large web sites, and other collections of information
- version control is track code changes, save initial version to git, update code and we save it into git, through time, we can check the code changes over time

- see and understand what we did when
- track down bugs
- go back to a previous version of the code

Terms

- directory -> folder on computer
- terminal / command line -> interface for text commands
- CLI -> command line interface
- cd -> change directory
- code editor -> word processor for writing code
- repository -> project or folder/place where project is kept
- Github -> website to host repositories online

Git Commands

- clone -> bring repository that is hosted somewhere like github into a folder on your local machine
- add -> track your files and changes in git
- commit -> save your files in git
- push -> upload git commits to a remote repo like github
- pull -> download changes from remote repo to local machine, opposite of push
- status -> shows all files that were updated, created, deleted that haven't been saved in commit yet
- commit -m "heading" -m "description" -> m means message, what and why of the commit you're making
- push -u origin master -> origin is location of git repository, master is branch to push to, u means upstream, this is where I want to push it to by default
- in future don't need -u, since that is default
- remote -v -> somewhere else not on computer, -v shows any remote repos that is connected to repo

- git branch
- git checkout -b -> switch bewteen branches or use -b to create a new branch

`ls -la`

- list everything in the directory including hidden folders
- git folder stores all files that save your commits or code changes, all changes recorded in history of repo including ones in github.com

ssh keys

- prove to github you're the owner of the account
- generate key locally

`ssh-keygen -t rsa -b 4096 -C "github email address`

- -t type of encryption
- rsa -b 4096 strength of encryption

key.pub

- upload into github interface
- public key, ok for other people to see key
- other key is private key, keep secure on local machine
- connect to github, push on github, use account, use your private key to show github that you created the public key mathematic proof that only private key can generate public key

`cat key.pub`

creating ssh key
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Github workflow
write code -> commit changes -> make a pull request

pull request

- if we didnt own the repository
- if we didn't have access rights
- if we need someone else to review our code
- merged in with rest of code

Local git workflow
write code -> stage changes (git add) -> commit changes (git commit) -> push changes (git push) -> make a pull request

Git branching -master branch (main or default branch)

- can create a feature branch
- updates on feature branch only seen on feature branch
- merge feature branch back later

## Demo

Some description!

## Subheader

Watch tutorial on YouTube

1. Open index.html in your browser
