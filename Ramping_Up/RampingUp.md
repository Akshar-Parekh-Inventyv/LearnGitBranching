# Level-2 Ramping UP 

## Task1 Detach Head
```
    git checkout c4
```
![alt text](image.png)

## Task2 Relative Refs
```
    git checkout c3
```
![alt text](image-1.png)

## Task3 Relative Refs #2
```
   git branch -f main c6
   git checkout HEAD~1
   git branch -f bugFix HEAD~1 
```
![alt text](image-2.png)

## Task4 Reversing Changes in a Git
```
    git reset HEAD~1
    git checkout pushed
    git revert pushed
```
![alt text](image-3.png)