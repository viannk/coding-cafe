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

### Question 9
The four steps of the repetitive Git loop are: Edit (modify files), Check (run git status), Stage (run git add), and Commit (run git commit).

### Question 10
README.md is automatically rendered on the main landing page of a GitHub repository to give visitors an immediate overview of the project.

### Question 11
gh auth login authenticates the machine using OAuth credentials, so Git doesn't prompt for a password every time you push.

### Question 12
The README.md file is displayed on the front page because GitHub automatically renders root README files as documentation for the repository.

### Question 13
No, git push uploads commits to GitHub; it does not change or alter local commit history.

### Question 14
A private repository exists on GitHub and is accessible only to you and invited collaborators. A non-existent repository does not exist on GitHub at all.
