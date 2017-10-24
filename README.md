# GIT CHEATSHEET

## How to commit your work for the first time in a new project:

* Initialize a repository: type git init. Command line should say "Initialized empty Git repository"
* Check the repository: type git status. It should show you the untracked files.
* Save your progress: track the file by adding it using git add followed by each of the filenames, one at a time.
* Check what has changed: type git status.
* Commit the changes: type git commit -m "commit message"

Success! If you type git status You should see "nothing to commit, working directory clean"

# Pushing your snapshot to GitHub:

* Go to github.com and create a new repository
* Add GitHub repository as a remote branch: Use git remote add origin git@github.com... (follow GitHub's instructions for this line)
* Send changes to repository: type git push origin master to send your committed changes.
* To pull from GitHub: Use the command git pull to keep your version up-to-date with the remote version