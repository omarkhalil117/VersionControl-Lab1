# Lab [1]

## 1.Create a SSH key and put the key in GitHub
### use command ssh-keygen -t ed25519 -m [My_Message]
![Q1](./Pics/1.1.png)
### get the public key from file id_ed25519.pub and add it to my profile
![Q1](./Pics/1.2.png)
### My key successfully added to my account
![Q1](./Pics/1.3.png)


## 2. Create a new local repo and a remote repo on GitHub, then make a file
## contains your full name, then push it to the remote repo, and send an invitation to me.
### initialize local repo with `git init` command
![Q2](./Pics/2.1.png)
### create remote repo named VersionControl-Lab1
![Q2](./Pics/2.2.png)
- check local repo status using `git status` command
- add **all** files to stage area using `git add .` command
- commit the added files with comment "First Commit" using `git commit -m "First Commit"` command
- check repo status and see my recent commit
![Q2](./Pics/2.4.png)
- connect my local repo with my remote repo using `git remote add origin [ssh-link]` command
- push my commit from local repo to my remote repo using `git push -u origin master` command
![Q2](./Pics/2.5.png)
## My commit successfully pushed to my remote repo
![Q2](./Pics/2.6.png)
## Sending invitation :D
![Q2](./Pics/2.7.png)
