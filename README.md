# git-certification

#  Installation
https://gist.github.com/Klerith/90a612344dc2d4e4455ea810fdacbe69

# Update/upgrade git on mac
brew install git
brew upgrade git


## Free eBook
https://git-scm.com/book/en/v2 

# Commands
git version
git --version

git help

- / abreviation
-- // full words
### create local repository
create the folder .git
```
git init
```

### in color red the files peding to commint
```
git status
```

![alt text](https://github.com/firedevelop/git-github-certification/blob/main/images/1.png?raw=true)


git log

### add: send files to stage
git add .

### exclude the file exclude.txt
git reset exclude.txt
// Now is missing the file

```html
git status
```

### comit: like snapshot
git commit -m "first commit"

### restore file
git checkout -- .

### U
means unt rack, when git no le da seguimiento a ese archivo  

### brach status
git branch
git status  

### rename branch
-m means modify, branch with the name master to main
```git branch -m master main ```

### reset (don't upload changes of one file)
1º track the files 
``` git add . ```
2º after track, untrack only one file
``` git reset 1.txt ```
3º git commit -m "."
4ª git push
5º the file 1.txt doesn't change on github


### commit by extension (path needed)
git add js/*.js

### .gitkeep (keep folder tracking when is empty)
myUploads/.gitkeep

### add whole folder
``` git add css/ ```

#### create folder and file one line
mkdir myFolder && myFolder/myFile.txt