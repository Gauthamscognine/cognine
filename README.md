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
Basically if someone is working upon a feature and he wants to switch between branches with or without adding the files . so if we want to move from one feature branch to another without making an commit , then we can make



