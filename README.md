# Git-alias
 A feature that can makes the Git experience simpler, easier and faster.

| alias              | Description   |
| ------------------ | ------------- |
| g | `git` |
| ga  | `git add` adds a change from unstages to stage changes, it tell git that you want to include this change into next commit. |
| gaa | `git add all` stage all (new/modified/deleted) files. |
| gb | `git branch` list the local branches |
| gba | `git branch -a [branch name]` list the local and remote branches |
| gbd | `git branch -d [branch name]` delete the branch |
| gbD | `git branch -D [branch name]` force delete the branch |
| gbnm | `git branch --no-merged` list branches pending to merge |
| gbr | `git branch --remote` list remote branches |
| gc | `git commit -v` |
| gca | `git commit -v -a` |
| gcm | `git checkout -b master` checkout the master branch |
| gcb | `git checkout -b [branch name]` |
| gcf | `git config --list` list the git config |
| gcmsg | `git commit -m` |
| gco | `git checkout [branch name]` checkout the given branch name |
| gd | `git diff` see the git difference |
| gl | `git pull` pull the latest changes |
| gp | `git push` push the changes |
| gpf | `git push --force-with-lease` force push the changes |
| grb | `git rebase [branch name]` rebase the changes with given branch |
| grbm | `git rebase master` rebase the changes with master branch |
| grba | `git rebase --abort` abort the rebase progress |
| grbc | `git rebase --continue` continue the rebase progress |
| gst | `git status` list the current changes |
| gstaa | `git stash apply` apply the latest stash to current branch |
| gpsup | `git push --set-upstream origin $(git_current_branch)` push the branch to upstream |
