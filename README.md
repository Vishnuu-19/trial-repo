Here's a list of some common Git commands and their uses:

git init: Initializes a new Git repository in the current directory.

git clone [url]: Clones an existing Git repository from a remote server to your local machine.

git add [file]: Adds a file to the staging area, preparing it to be committed.

git add .: Adds all changes in the current directory to the staging area.

git commit -m "[commit message]": Commits the staged changes to the repository with a descriptive message.

git status: Displays the status of the working directory, including untracked, modified, and staged files.

git diff: Shows the difference between the working directory and the staging area.

git diff --staged: Shows the difference between the staging area and the last commit.

git log: Displays the commit history of the repository.

git branch: Lists all the branches in the repository.

git branch [branch_name]: Creates a new branch with the given name.

git checkout [branch_name]: Switches to the specified branch.

git checkout -b [branch_name]: Creates a new branch and switches to it.

git merge [branch_name]: Merges the specified branch into the current branch.

git remote: Lists all remote repositories.

git remote add [name] [url]: Adds a new remote repository with the specified name and URL.

git push [remote] [branch]: Pushes the commits from your local branch to the remote repository.

git pull [remote] [branch]: Fetches the changes from the remote repository and merges them into the current branch.

git fetch [remote]: Fetches the latest changes from the remote repository without merging.

git reset [file]: Unstages the specified file, keeping the changes in your working directory.

git reset --hard: Resets the staging area and working directory to match the last commit.

git revert [commit]: Creates a new commit that undoes the changes made in the specified commit.

git stash: Temporarily shelves changes that are not ready to be committed.

git tag [tag_name]: Creates a new tag at the current commit.

git rm [file]: Removes a file from both the working directory and the Git repository.
