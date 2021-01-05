# Github101
All in one repo for your github problems!

# What's Github?

## Difference between git and github?
![Screenshot](Gitvs_Github-1a-1.webp)

![Screenshot](1_NP_GK24IxuH89G8b3Uq5PQ.png)


Github Daily

#### 1. Initialize a repo in a local directory and clone an existing repo to it:
```
a. git init
b. git clone <https link for the existing github repo>
c. Make your code changes
d. git add -A
e. git commit -m "This is my first commit"
f. git push --set-upstream origin master
<Note here: your default branch could be named  "master" or "main"; check git branch --list>

```


#### 2. Inspect and Compare:
```
git log
>>> show commits in the current branch history
git log branchB...branchA
>>> show commits that are in A and not in B, no space in b/w dots

```
#### 3. Branches:
```
git branch -l
>>> List all the branches in your repo
git checkout -b branch1
>>> Checkout/Create  a new branch branch1
git checkout master
>>> Switch to branch master


```
