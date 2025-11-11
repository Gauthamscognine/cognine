## A sample POC for practicing of GITHUB

## 1. Initialize Git
git init 
Add files into it 
## 2. Add Files
git add . for all files 

## 3. Commit Changes
git commit -m "Initial commit"

## 4. Connect to GitHub
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git remote -v

## 5. Push to GitHub
git push -u origin main

## 6. Clone an Existing Repo

git clone https://github.com/USERNAME/REPO-NAME.git





## Having the same file content  conflict 

When we 2 developers are making changes in the same file and then one commits and pushes and when another tries to push  , he gets merge conflicts 
In the file he can see 
 <!-- <<<<<<< HEAD
console.log('My change');
console.log('Teammate change');
Now u can change the content of the file accordingly and then add , commit and then push  -->
## STASH 
Basically if someone is working upon a feature and he wants to switch between branches with or without adding the files and commiting them  , then we can make use of stash 

## stash a file 
git stash 

## remove from stash 
git stash pop  - will remove from thr stash and also delete the stash 
git stash apply - will just remove from the stash 







## A Sample POC for Practicing GitHub  

## 1. Initialize Git  
git init  
Add files into it  

## 2. Add Files  
git add .   (for all files)  

## 3. Commit Changes  
git commit -m "Initial commit"  

## 4. Connect to GitHub  
git remote add origin https://github.com/USERNAME/REPO-NAME.git  
git remote -v  

## 5. Push to GitHub  
git push -u origin main  

## 6. Clone an Existing Repo  
git clone https://github.com/USERNAME/REPO-NAME.git  

---

## Having the Same File Content Conflict  

When two developers make changes in the same file and one commits and pushes first, the other will get **merge conflicts** when trying to push.  

In the file, you can see something like this:  

<!-- <<<<<<< HEAD
console.log('My change');
console.log('Teammate change');
Now u can change the content of the file accordingly and then add , commit and then push  -->

Now, you can change the content of the file accordingly, then **add**, **commit**, and **push** again.  

## STASH  

If someone is working on a feature and wants to switch between branches with or without adding and committing files, we can make use of **stash**.  

### Stash a file  
git stash  

### Remove from stash  
git stash pop   → will remove from the stash and also delete the stash  
git stash apply → will just apply the stash but keep it saved  





