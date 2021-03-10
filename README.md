Learning how to work with github by Gwen Faraday \
Source: https://www.youtube.com/watch?v=RGOj5yH7evk \
 \
To initialize a git repository in a local folder \
->git init \
 \
To connect a locally created project to a remote Git repository \
You need to add the origin parameter first so create an empty repo on Github \
then use ->git remote add origin https://github.com/astr0n0mer/My-Github-Repo.git \
then you can use ->git push command to push it online \
 \
To clone a github repository in your local machine \
->git clone https://github.com/astr0n0mer/My-Github-Repo.git \
 \
To see files that were created / updated / deleted but not committed yet \
->git status \
 \
To make git track your files (or to stage your changes) \
->git add file1.txt, file2.java \
OR USE ->git add . \
 \
To commit changes made in your repository (Commit title is mandatory and commit description is optional) \
->git commit -m "My_commit_title" -m "My_commit_description" \
 \
To push your commits to your remote Git repository \
->git push origin [branch_name_that_you_want_to_push_into] \
Eg: ->git push origin master \
