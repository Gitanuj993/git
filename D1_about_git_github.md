# Welcome To the Git user Guide Simplified Part 1.
**In this Section We will answer of the following !**
1. What is git ? 
2. What is github ?
3. How to use them ? , 
4. Can we use github from our pc Command line ? ,
5. Why commands line Interface is more comfortable?
6. What is Repository?
7. What is "push" ?
8. What is "pull" ?
9. What is a "pull request" ?
10. What is "Review" ?
11. What is "Discussion" on GitHub?



## Lets Explore them and if you have any other Questions  just let us know ?
1. What is git ?
```txt
Ans : Git is a software which is used when you are working on a projects, lets say it To-do "Application",
During the projects you will  made plenty of changes and introduces new features.
what if you shipped a project and it goes down or it simply do not work and you want previous version of your projects.
as you already overwrtten privious version then you can't go back to previous version of the projects , you have to manually
remove all changes and you have to write previous version of the project.

To resolve above query or issue , git is introduced to manage previous changes,
or in techincal term we call it previous versions .
thus  git is a versino control system which keep track of new and old changes of the project.

Benefits of git : We can easly see previous changes, we can go back to previous versions of the project.
we can see difference in previous code and new changed code.

How git works for practical use. ?
To make new changes on the file/project/repository 
1. first we have to add file(s) to staze , to ensure that which files we want to add into the project to track by git.
2. when ensuring this changes are correct enough to attack them into the project we , add them into git , or commit into the git version control,
with a message like what changes? what is in the new chages ?
```

2. What is github ?
```txt 
Github is cloude storage for our projects which we call repositories. git hub contains our projects in the form of repositories or directories.
or inshort 'repo'.

Github is a place to store our projects that we can access them anywhere with our github credentials ( id and password ).
github is like google drive which can be used to store our work in the form of projects.

Github main role is for cloud storge and opens source contributions.
github do far more things than storing your code online.

Features of Github :
1. Store your code online.
2. Other users can see your code and made changes from their end and can contribute to your project, if you allow
3. You can contribute to other projects on the github , using forks ( work on other projects with your own instance ).
4. You can use to log in into other accounts.
5. You can Host your website from github pages.
6. You can host your project from other plateform like vercel,railway,render with access to your code on github , without manually uploading projects seperately on 
other plateform.
7. Github Actions is a feature which allow you to do DevOPS operatations like automation , CI/CD/

```
3. How to use them git and github ?
```txt
1. Create a free account on github and use github online or download its desktop application.
2. git is command line tool and it also has GUI interface . install git from : git.org
3. setup git and link it with your github.
4. write code in your laptop/computer which is called local machine, then using git add your code to remote repository which is on github.

```
4.  5. git and command line interface .
```txt
yes ,git is a command line tool, but it also has a graphical user interface.
CLI is more recommended as when you know commands then your efficiency and productivity get increased.
it is easy from keyboard to make changes and perform git operations.

```
6. What is a repository ?
```txt
a repository is like a directory which contains our files and code. repository widely contains projects.
a repository may contains main files and code of the projects.
repository and project words used interchangeable to convey files and code.
```
7.  What is "pull"?
```txt
'git pull ' is a gits command whic is used to fetch repository data.
to pull a codes and files from a repository you have to provide its locatiions or branch.
like " git pull origin main" , " git pull origin features"
what is branch ?
branch is an instance of the main/master or default projects.
like in above examples main is the default instance of the project which is used for production of code.
feature branch is used another instance of the project for developing new features and then adding the changes to the defualt branch.
this addtion is callled merging or branch merge.
```
8. What is push ?
```txt 
It is a git command to merge your changes on local machine to remote branch or repository.
if you want to merge feature branch to main or defualt branch you have to request to merge your changes/branch , 
this request is called "Pull Request or PR " many other teams and developers will check your changes ( review it ) then 
if the PR is meets the standards then they approve it, 
owner of the repository will accept your pull request and merge your changes to the main branch.
```
