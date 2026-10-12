<h1>Commands</h1>
git init                          --> initialization<br>
git remote add origin url-name    --> connect repo with vscode<br>
git remote -v                     -->verify remote<br>
git branch                        -->to check branch<br>
git branch -M main                --> renaming default branch as main<br>
git add .                         --> adding file<br>
git commit -m "comment"           -->commit all files(green)<br>
git status                        -->checking commited file<br>
git  push -u origin main          -->pushing to remote repo(next push--> git push)<br>

<br>
<h2>Branching</h2>
git checkout -b branch-name       -->to create new branch<br>
git branch -d   branch-name       -->to delete branch<br>
git diff branch-name              --> to compare two branches<br>
git pull origin  branch-name      -->pulling from remote repo<br>
git merge branch-name             -->merge two branches if there is no conflicts(change in same line)<br>
<br>
<h2>Undoing changes</h2>
git  reset file-name                                --> undo last commit<br>
git reset head~1                                    --> commit goes  back one step<br>
git push --force-with-lease origin <branch-name>    --> to reset on remote repo
git reset   commit-hash                             --> go back  to specific commit<br>
git reset --hard  commit-hash                       --> changes are done vscode also<br>






<h2>Cloning</h2>
git clone <url>                   -->copying  repo<br>
