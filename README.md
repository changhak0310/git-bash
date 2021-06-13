# git-bash
## create a new repository on the command line
```
echo "# github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/changhak0310/git-bansh.git
git push -u origin main
```

## push an existing repository from the command linegit 
```
git remote add origin https://github.com/changhak0310/github.git
git branch -M main
git push -u origin main
```

## Add
```
git init
git add .
git commit -m "커밋 메시지"
git push
```

## Modify
```
git status
git add *
git commit -m "수정됨"
git push
```
