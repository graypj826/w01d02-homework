Part 1 - Github
Questions
1. "git init" creates a git repository inside of the folder 
2. "git add ." starts tracking files
3. "git commit -m ["message"] " moves the files currently being tracked to the staging area

part 1, 2nd Commit
1. "git pull" will pull any changes from the remote repository to the local
2. "git rm --cached <file>" will also remove a staged file.
3. "git revert <commit id>" will revert the branch back to the version before the identified commit, it's described online as an inversion because the unwanted commit remains in the log and the reversion is logged as the next step after the unwanted commit.
4. "--" indicates to git that you will be using an option from the command. For example. "git rm --cached" option indicates that you want to remove the cached files in the staging area. when removing files it is important to use -- becaus "git rm <file>" will delete the file from the working directory and stages the deletion. "-- cached" preserves the local file.
5.  you may want to revert the file back to a previous commit if there is an error in the committed files or you don't like the changes after all. 

