# Git training
This document includes basic instructions for how to use Git.

## Basics

Step 1: Fork Project <br>
Step 2: Clone: $ git clone https://git-repo-url<br>
Step 3: Create branch: $ git checkout -b branch-name<br>
Step 4: Do work work work work work<br>
Step 5: Add the changes<br>
                $ `git add -A` <br>
                            OR<br>
                $ `git add file-name`<br>
Step 6: Commit the changes<br>
                $ `git commit -m “Introduction”`<br>
Step 7: Push to fork<br>
                $ `git push origin branch-name`<br>
                            OR<br>
                $ `git push origin head`<br>
Step 8: Create a Pull Request/Merge Request<br>

Repetitive work<br>
origin: is the fork<br>
upstream: is the original repository/repo<br>

$` git remote add upstream https://github.com/DevAppLand/GitTraining`<br>

Step 1: `git pull upstream master`<br>




NB:<br>
To get the branch name and the project status: $ `git status`
