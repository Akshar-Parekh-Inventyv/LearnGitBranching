# Level 2 To Origin And Beyond -- Advanced Git Remotes!

## Task1 Push main
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

## Task2 Merging with remotes
```
    git checkout main
    git pull
    git merge side1
    git merge side2
    git merge side3
    git push
```
![alt text](image-1.png)


## Task3 Remote tracking
```
    git checkout -b side
    git commit
    git branch -u o/main
    git pull --rebase
    git push
```
![alt text](image-2.png)


## Task4 Git push arguments
```
    git push origin main
    git push origin foo
```
![alt text](image-3.png)


## Task5 Git push arguments -- Expanded!
```
    git push origin foo:main
    git push origin main^:foo
```
![alt text](image-4.png)


## Task6 Fetch arguments
```
    git fetch origin c6:main
    git fetch c3:foo
    git fetch origin c3:foo
    git checkout foo
    git merge main
```
![alt text](image-5.png)


## Task7 Source of nothing
```
    git push origin :foo
    git fetch origin :bar
```
![alt text](image-6.png)


## Task8 Pull arguments
```
   git pull origin c3:foo
   git pull origin c2:side 
```
![alt text](image-7.png)

