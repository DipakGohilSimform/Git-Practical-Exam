# Git- Practical Exam 

  

## 1. Pull and Merge difference  

- Make example of pull request and two branch merge event. 

  

1. create a Dev branch.   
  


2. After commit Push this new branch.  

  

3. Create Pull Request on GitHub.  

  

4. After approving the pull request dev branch will be merged with the master branch. In this case we own the master branch so we can approve the pull request.
  
  

## 2. Rebase 

- Try to rebase feature branch with master branch  

```sh 

git rebase master  

``` 
- rebase is used to maintain a clean project history.
  

1. push master branch after the commit. 

  

2. create another branch named feature. 

  

3. push this feature branch after commit. 

  

4. Now to rebase feature branch with master branch we have to write "git rebase master " command.



  

## 3. Change commit message 

- Commit push on commit in feature branch and then change commit message 

  

```sh 

git commit --amend -m "changed commit message" 

``` 

  

## 4. cherry pick 

- Pick some commits from feature branch to master branch 

  

```sh 

git cherry-pick (commit-id) 

``` 

- Example:


```sh 

git cherry-pick adff5634aa38365e2d32c2a9fdb30e8c5fa44528

``` 

  

## 5.  Drop commit 

- Remove some commit from feature branch. 

  

```sh 

git reset --hard HEAD~2 

``` 


 

- with this command the last two commits will be removed.  

  

- To remove the last commit from git, we can simply run git reset --hard HEAD^   

  

- If we want to remove multiple commits from the top, we can run git reset --hard HEAD~2 to remove the last two commits.  

  

- We can give the number of commits which we want to remove. 
