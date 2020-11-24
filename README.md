# how_to_use_git

```
# you want to create new brach from specification commit.
git clone 
git checkout -b <new branch name> <commit_id>

# you want to change remote repository url
git remote set-url origin <new github repository url>
git branch -M main
git push -u origin main

# you want to create and add new remote repository
git remote add <new repository name ex) myrepo> <new repository url>
# create and switch new branch having repository
git branch -M main
# if create and add new branch from already exists commit
git checkout -b main 9a7315a4c7e37e428321231d0cfc9c4590e9d609
# push you create branch to upstream respository
git push -u myrepo main
# create work branch
git checkout -b development
# push you create branch to upstream repository
git push -u myrepo development

# you create branch upload remote repository.
git push -u <new repository name ex) myrepo> main
# you want to create 
git checkout -b <new branch name> <commit_id>
```
