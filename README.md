## 3.2 Assignment
# Q: what is GitHub Authentication and how what methods available to be implemented?

- git init | To initialize existing directory as a Git Repository |
- git clone [url] | retrieve an entire repository from a hosted location via URL|
# Stage & Snapshot
- git status | show modified files in working directory, staged for next commit |
- git add[file] | add a file as it looks now to your next commit(stage) |
- git reset [file] | unstage a file while retaining the changes in working directory |
- git diff | diff of what is changed but not staged
- git diff --staged | diff of what is staged but not yet committed |
- git commit -m "[descriptive message]" | commit your staged content as a new commit snapshot |
# Branch & Merge
- git branch | list your branches. a* will appear next to the currently active branch
- git branch [branch-name] | create a new branch at the current commit
- git checkout | switch to another branch and check it out into your working directory
- git merge [branch] | merge the specified branch's history into the current one
- git log | show all commits in the current branch's history

# 4 commands that I think are most used
- git add . or git add[file] 
- git status - 
- git commit -m "<commit message>"
- git push

Above are the 4 commands that are are used when doing my CICD capstone project. Most of the time the workflow yml codes that are pushed to run github action will result in error. I have encountered endless numbers of errors and had to use the above four commands many times.

In addition, git branch and git checkout are 2nd most used commands to check which branch I am currently working in and to toggle to the branch that I want to be working in.