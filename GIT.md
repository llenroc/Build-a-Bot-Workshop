#Git & npm Cheatsheet

###Common git commands used for this lab 

```shell
git init
```
Initializes the current folder as your local Git repository

```shell
git remote add origin https://github.com/yourusername/yourrepositoryname.git
```
Points Git to the location of the remote repository

```shell
git pull origin master
```
Incorporates changes from the remote repository into the current branch

```shell
git add .
git commit -m "<Your commit message goes here>"
git push origin master
```
Adds/ stages all files in the current directory and commits it to the local repository. The commit is then pushed to the remote repository.

###Common npm commands used for this lab

```shell
npm install npm -g
```
Updates npm to the latest version

```shell
npm init
```
Starts your nodejs project in the current directory. You may fill in the description and author name here.

```shell
npm install --save botbuilder
npm install --save restify
```
Installs the botbuilder and restify packages required to build the bot in the lab.

