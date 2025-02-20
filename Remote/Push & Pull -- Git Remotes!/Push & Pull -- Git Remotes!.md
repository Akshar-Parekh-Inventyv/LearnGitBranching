# Level 1 Push & Pull -- Git Remotes!

## Task1 Clone intro

```
    git clone
```
![alt text](image.png)

## Task2 Remote Branches
```
    git commit
    git checkout o/main
    git commit
```
![alt text](image-1.png)

## Task3 Git Fetchin'
```
    git fetch
```
![alt text](image-2.png)


## Task4 Git Pullin'
```
    git pull
```
![alt text](image-3.png)


## Task5 Faking Teamwork
```
    git clone
    git fakeTeamwork main 2
    git commit
    git pull
```
![alt text](image-4.png)

## Task6 Git Pushin'
```
   git commit
   git commit
   git push 
```
![alt text](image-5.png)

## Task7 Diverged History
```
   git clone
   git fakeTeamwork main 1
   git commit
   git pull --rebase
   git push 
```
![alt text](image-6.png)

## Task8 Locked Main
```
   git checkout -b feature
   git push
   git branch -f main c1
```
![alt text](image-7.png)
