# Git-Cheat
Cheat sheet for normal git operations

Steps for normal update into master:-

Step 1: Clone repo using its URL into your local pc directory using git bash.

* by command "git clone  https://github.com/bhaskarsdose/Git-Cheat "

Step 2: Change whatever you want like add, upgrade or delete after doing this go into the directory and open Git bash in the same directory and type,

*  "git add -A"

Step 3: Commit what ever you have changed by,

* "git commit -m 'Directory: Readme updated' "

Step4: Push your work into master directory,

* "git push master origin" or if it doesn't work "git push -f origin master"

Its done.....................

Steps For adding different branches:-

* For checking out from branch,

  "git checkout branch_name"

* For adding new branch,

  "git checkout -b name_of_branch"

* For checking the status of added files,

  "git status"

* For updating specific files,

  "git add Tools/GIT_Test/GIT_Success.txt"

Commands for changing branch on local machine like in Ardupilot:-

* For seeing the branches

  "git branch -a"

* For locking the branch(press tab for getting the exact value of X)

  "git checkout Copter-4.0.X"