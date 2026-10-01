# Lab 4 Notes

### Question 1
--global applies configuration settings across all repositories for the current user. Leaving it out sets the configuration only for the current repository.

### Question 2
ls -a reveals the hidden .git directory. Inside it are internal configuration files, commit history logs, object databases, and branch references.

### Question 3
Git offered to track many untracked files. Entries like .venv/ and compiled python files are code/dependencies that I did not write.

### Question 4
All files inside .venv/ and other ignored patterns vanished from the untracked list in git status.

### Question 5
.gitignore should be committed so everyone collaborating on the project shares the exact same rules for ignoring untracked files.

### Question 6
README.md moved from untracked files to changes to be committed. In the three-places model, it moved from the Working Directory to the Staging Area (Index).

### Question 7
Git printed a commit summary with the branch name, short commit hash, and file change statistics showing how many files changed and lines added/deleted.

### Question 8
The first seven characters are the short commit SHA-1 hash. They act as a unique identifier for that specific commit snapshot.x
