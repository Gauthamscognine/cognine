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

----------------------------------------------------------------------------------------------------------------------------------

## Having the Same File Content Conflict  

When two developers make changes in the same file and one commits and pushes first, the other will get **merge conflicts** when trying to push.  

In the file, you can see something like this:  

<!-- <<<<<<< HEAD
console.log('My change');
console.log('Teammate change');
Now u can change the content of the file accordingly and then add , commit and then push  -->

Now, you can change the content of the file accordingly, then **add**, **commit**, and **push** again.  


----------------------------------------------------------------------------------------------------------------------------------

## STASH  

If someone is working on a feature and wants to switch between branches with or without adding and committing files, we can make use of **stash**.  

### Stash a file  
git stash  

### Remove from stash  
git stash pop   → will remove from the stash and also delete the stash  
git stash apply → will just apply the stash but keep it saved  


----------------------------------------------------------------------------------------------------------------------------------

## Rebase 

Suppose you are in main branch , and then u moved to a feature branch . while you are working on a feature branch , some other developer , made changes in main branch and then pushed into github . 

main --------- COMMIT(A) , COMMIT(B) -- made by some other developer and pushed 
feature  ------ COMMIT(C) , COMMIT(D) -- made commits in detaure by you . 

Now if u want to maintain a clean commit history and wana add the commmits u below the main branch commits . 
you can make use of rebase . 

## Rebase branches . 
git rebase [from branch ] [ to branch ]
example  -  git rebse feature main 

----------------------------------------------------------------------------------------------------------------------------------


## CHERRY PICK 

consider a situation where u wanna add a commit from one  branch to another branch without merging the whole branch .
Here u can make use of git cherry pick 
It allows you to merge a specific commit from one to another branch 

## cherry pick
git checkout main (The branch u wanna add the commit in )
git cherry-pick [commmit hash of the specific commit ]

----------------------------------------------------------------------------------------------------------------------------------


