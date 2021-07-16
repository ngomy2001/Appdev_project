# Init project
Hello world! Now I will guide you how to setup project from scratch.


## Init Express project

Step 1: Install express-generator globally.
```sh
$ npm install -g express-generator
```

Step 2: Generate new project by using these command line.
```sh
$ express --view=ejs Appdev
```

>**NOTE**: Template engine is EJS and Project's name is Appdev

Step 3: Install all depencency packages
```sh
$ npm install
```

## Setup Git and GitHub

Step 1:  Initialized empty Git repository in working directory
```sh
sudo git init
```
Step 2: Move all files from working tree to staging area
```sh
sudo git add .
```
Step 3: Create a first commit
```sh
sudo git commit -m "Init project"
```
Step 4: Connect to remote repos on GitHub
```sh
git remote add origin https://github.com/ngomy2001/Appdev_project.git
```
Step 5: Push code on Remote Repo
```
git push -u origin master
```