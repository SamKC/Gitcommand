# Basic Git commands

### Creating a repository online for the <b>1st time</b>!
```sh
# navigated into your folder you want to put on Github
$ touch README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/SamKC/Gitcommand.git
$ git push -u origin master
# put in username & passwords
```
### When adding on to your repository online with changes
```sh
$ git add .
$ git commit -m ' what has changed'
$ git push or git push origin master
# put in username & passwords
```
## git markdown for cheatsheet by google

### No more username & password input for every push
```sh
$ git remote set-url origin git@github.com:your username/yourReponame.git
$				      SamKC/Gitcommands.git