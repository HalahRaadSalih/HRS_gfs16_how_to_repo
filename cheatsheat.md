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


### Help  someone else with their code 

first, find the code on github that you want to contrubute to.

Then fork it.



```shell
$ git clone git@gitbub.com:< your username>/<name repo>.git
```

Then make changes that you think are important. 


```shell

$git add <your files>
$git commit -m "A really through explanation of what we did since this is someone else's work"
```

Finish what you started wirking on, then push up any addtional commit.

File a pull request with the commits in that you want to share. Make sure you have a good explanation in the pull request of what this is, what it's intended to do.  and some nice language.