
# Welcome AT !

### How to set-up git in machine , { termux , linux , console }

> We will go with termux , However process is same for the remaining one !

> Fist of all we install the git in our local machine by using a command , as machine works in commands not by intentions

1. code look like this : ``  pkg install git ``

2. After the git is downloaded, you have tell git your identity as git don't works for ghosts.
intorduction about git setup !

3. git setup include downloading of git using internal command and confiigure it for according to your github  profile name , email id and SSH authentication token as password not your gitHub login authentication password ,
github and git uses a different authentication method for verification.

`` git config ``
##### Lets have a look on the above command , git is used to specify your task , it shows where are you doing ,
``config``
> shows what are you doing 

4. first of all we should add a global configuration for your machine without it you didn't able to tell who are you ?

`` git config --global user.name "Gitanuj993" ``
`` git config --global user.email "gleuser83@yahoo.in" ``

5. this process is mandatory but it doesn't connect your machine to remote machine which is your github account

`` $ git config --global credential.helper store  ``
? Credential Storage ?

`` git init ``
from above command you would initialize git in the folder

`` git clone ``
It is used to clone a repo from the remote machine

`` git status``
It states the info and status of the working repo 
it states whether repo is clean or  untracebale files 

`` git add . ``
It add and stagged all the files for tracking and ready to commit for vesrion history of the repo
`` git add file1.py ``
WE can also  add individual fils 

`` git commit -m " initial commit "  ``
it creates a new snapshots of stagged files with version name and add commit and description of the snapeshot "

`` git push -u origin main `` or `` git push --set-upstream origin main  ``
`` -u is the short form of --set-upstream ``
it pushes all the commited files to the remote repo called origin and into the main branch
this commands also help us to link that branch to remote branch to use pull and push the code without specifing , orign and main eachtime

`` git push origin main ``
Used to push code into remote machine or repo origin main
`` --tags ``
used to push tags 

`` -d ``
Used to delete a remote branch 

`` -f ``
`` -force ``
Used to push code focefully 

`` git remote add origin https://github.com/Gitanuj..git``

