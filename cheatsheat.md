#Git Cheatsheet

### Start a new project

```shell
$mkdir project_name
$git init
$touch readme.md
$git add readme.md
$git commit -m "initial commit"
```


### Do some work and then save it

First, do some work!
Make some changes, put them in the box and then label the box

```shell 
$git status
$git add <whatever file>
$git status
$git commit -m "I made a bunch of changes, there are so many detials"
```

### Share my wrok with the world, yo!

```shell

$git remote add origin github@github.com:<github username/repo_name>
$git push -u origin master
```