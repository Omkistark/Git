## https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf

*git add* adds a change in the working directory to the staging area
*git commit* create a snapshot of the staged changes along a timeline
*git commit -a*	Stages files automatically  
*git log -p*	Produces patch text  
*git show*	Shows various objects  
*git diff*	Is similar to the Linux `diff` command, and can show the differences in various commits  
*git diff --staged*	An alias to --cached, this will show all staged files compared to the named commit  
*git add -p*	Allows a user to interactively review patches to add to the current commit  
*git mv*	Similar to the Linux `mv` command, this moves/renames a file  
*git rm*	Similar to the Linux `rm` command, this deletes, or removes a file  
  
  # REVERT  
*git checkout* is effectively used to switch branches.  
*git reset* basically resets the repo, throwing away some changes.  
*git commit --amend* is used to make changes to commits after-the-fact, which can be useful for making notes about a given commit.  
*git revert* makes a new commit which effectively rolls back a previous commit. It’s a bit like an undo command.  

  # MERGE  
git branch	Used to manage branches  
git branch <name> 	Creates the branch  
git branch -d <name>	Deletes the branch  
git branch -D <name>	Forcibly deletes the branch  
git checkout <branch> 	Switches to a branch.  
git checkout -b <branch>	Creates a new branch and switches to it.  
git merge <branch> 	Merge joins branches together.  
git merge --abort	If there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action.  
git log --graph --oneline	This shows a summarized view of the commit history for a repo.  
