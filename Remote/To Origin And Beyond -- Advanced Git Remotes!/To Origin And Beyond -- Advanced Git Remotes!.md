# Level 2 To Origin And Beyond -- Advanced Git Remotes!

## Task1 
```
    git checkout main
    git pull
    git checkout side1
    git rebase main
    git checkout side2
    git rebase side1
    git checkout side3
    git rebase side2
    git checkout main 
    git rebase side3
    git push
```
![alt text](image.png)

## Task2
```
    git checkout main
    git pull
    git merge side1
    git merge side2
    git merge side3
    git push
```
![alt text](image-1.png)