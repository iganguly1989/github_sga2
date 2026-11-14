Create Folder(Repo) first:->
mkdir git_sga2

Point to that folder:->
cd git_sga2

Sets the author name & email recorded in commits in this local repository:->
git config --global user.name "Indrajit Ganguly"
git config --global user.email iganguly1989@gmail.com

Check the git Version:->
git version

Initialized existing Git repository:->
git init

Shows changed, staged, and untracked files in the working directory:->
git status

Stages the HTML file, so this can be included in the first commit:->
git add index.html

Saves the initial project files as the first commit:->
git commit -m "Modified with second Commit"

Records the change made to index.html:->
git log

Create a feature branch:->
git branch feature

Make changes to the file and commit them to the feature branch:->
git add about.html

Records the new feature on the feature branch:->
git commit -m "Changes made on about.html file & commit to feature branch"

Switch back to the main branch:->
git switch main

Changes made on about.html file & commit to feature branch:->
git merge feature

Display the commit history showing all changes:->
git log -p

Create a .gitignore rules file:->
type nul > .gitignore

Configure it to ignore:->
notepad .gitignore
echo Test log > app.log
mkdir temp
echo Temporary file > temp\test.txt

Checks that a log file and a file inside temp/ are ignored by Git:->
git check-ignore -v app.log temp/test.txt
git add .gitignore
git commit -m 

For Undo Operation:->
notepad contact.html

Creates an additional commit that will be undone:->
git commit -m "Add contact page for undo functionality"

Undoes the latest commit by creating a new commit that reverses its changes:->
git revert --no-edit HEAD

Connect with GitHub:->
git remote add origin https://github.com/iganguly1989/github_sga2.git

Push the main branch:->
git push -u origin main

URL of my GitHub repository:
https://github.com/iganguly1989/github_sga2
