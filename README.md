# Working with Github by Gwen Faraday  
Source: [Youtube](https://www.youtube.com/watch?v=RGOj5yH7evk)  
  
1. To initialize a git repository in a local folder  
`git init`  
  
2. To connect a locally created project to a remote git repository  
You need to add the `origin` parameter first, so create an empty repo on Github  
then use `git remote add origin https://github.com/astr0n0mer/My-Github-Repo.git`  
then you can use `git push` command to push it online  
  
3. To clone a github repository in your local machine  
`git clone https://github.com/astr0n0mer/My-Github-Repo.git`  
  
4. To see files that were created / updated / deleted but not committed yet  
`git status`  
  
5. To make git track your files (or to stage your changes)  
`git add file1.md, file2.java`  
`git add .`  
  
6. To commit changes made in your repository (Commit title: mandatory & commit description: optional)  
`git commit -m "My_commit_title" -m "My_commit_description"`  
  
7. To push your commits to your remote git repository  
`git push hyperlink branch_name`  
`git push origin master`  
`git push`  
