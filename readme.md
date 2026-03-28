
1.Code update kiya,website crash hogyi coder ko muje revert back karna padega
2.Ownershp of code 

<!-- Configure git -->

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


you can verify the configuration

git config --list


<!-- How to see hidden folder -->

in Mac: CMD+shift+.
in windows:
In windows 11: click the view dropdown(three dots)
show>hidden items.

to start tracking of a particular folder

git init

<!-- start tracking -->

git add "filename"
<!-- Add file to staging area -->
git add .


git status
<!-- What changes are staged, not staged, untracked  -->

git diff
<!-- q for exit -->
<!-- What has been changed line by line in your report -->
<!-- it shows which part of the report have been edited but are not yet staged for commit -->


<!-- Commit file -->
git commit -m "message"
git diff

<!-- Remove file from staging area -->
git reset <file>
git restore --staged <file>

<!-- Get logs of commit -->

git log
git log --oneline
git show <hash>

<!-- Revert the changes -->

git reset --hard <hashCode>
git revert <hashCode>
<!-- git add . -->
<!-- git commit -m -->


<!-- How to create a branch -->

git checkout -b <branch-name>

<!-- Mrgeing of branch -->

git merge <branch-name>
<!-- Delete a branch -->
git branch -d branch-name
git branch -D <branch-name> (hunmerged also);

<!-- ESC: wq ---> helpful(Escape the writing mode,save and quit ) -->
<!-- i:insert mode -->

<!-- how to change the name of the branch -->

git branch -m <branch-name>

<!--Git slash -->
allows you to temporarily save your uncomitted changes (both staged and unstaged ) in a "stash" and revert your working directory back to the last commit.

<!-- git slash -->
<!-- git slash list -->
<!-- git slash apply-->
<!-- git slash apply stash@{1} -->
<!-- git slash pop -->
<!-- git slash clear-->

<!-- working with github -->
<!-- git remote add origin <url> -->
<!-- git branch -M main -->
<!-- git push -u origin main -->

<!-- git pull origin main -->
<!-- git pull --rebase origin main -->

<!-- git branch -r -->

<!-- git push origin --delete feature -->