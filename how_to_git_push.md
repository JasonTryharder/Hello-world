**How to add a new repo on github**
1. create a new Git repo in [github.com](https://github.com/JasonTryharder/Hello-world.git)
2. find the link to your repo
3. `cd` to your local project dir and do `git init`
4. `git remote add origin` remote repo URL
5. if some of your folders/files are from other repo and **chances** are they will have **.git/** folder in them, to see ahidden folder do `cd .`and `tab tab`
6. if there is `.git/` folder, you can decide to wethere to make it [submodule](https://github.community/t/adding-a-folder-from-one-repo-to-another/781/2) or delete the `.git/` by `rm -rf .git` 
7. `git add .` will add everything inside dir, individual add by `git add readme.md`, use `git add -u` to add only updated tracked files
8. `git commit -m "mesage you want to add to this commit"
9. `git branch -M main` to set the branch name to be main, ( master if you want)
10. `git push -u origin main` if this is first time, afterwards use `git push`

**How to remove a git directory** 
1. `git rm -r --cached FolderName`
2. `git commit -m "Removed folder from repository"`
3. `git push origin master`
