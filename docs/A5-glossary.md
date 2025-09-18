# Git Glossary

**Add**: Staging changes to include them in the next commit.

*Example*: `git add file.txt`

**Blame**: Shows line-by-line changes for a file, including who made each change.

*Example*: `git blame file.txt`

**Branch**: Independently evolving versions of a project. The default branch is usually called `master` or `main`.

*Example*: Create a new branch with `git branch feature-branch`.

**Checkout**: Switching between different versions of files.

*Example*: `git checkout feature-branch`

**Cherry-pick**: Applying changes from a specific commit to a different branch.

*Example*: `git cherry-pick commit_hash`

**Clone**: Making a copy of a remote repository on your local machine.

*Example*: `git clone https://github.com/user/repo.git`

**Commit**: A snapshot of your repository's changes at a specific point in time.

*Example*: `git commit -m "Fixed bug"`

**Config**: Configures Git settings.

*Example*: `git config --global user.name "Your Name"`

**Diff**: A display of changes between commits or branches.

*Example*: `git diff`

**Fetch**: Downloading changes from a remote repository without integrating them.

*Example*: `git fetch origin`

**Fork**: A personal copy of another user's repository.

*Example*: Fork a repo on GitHub via its interface.

**Gitignore File**: A file that tells Git which files or directories to ignore in a project.

*Example*: `*.log` in `.gitignore` ignores all `.log` files.

**HEAD**: A reference to the last commit in the current checked-out branch.

*Example*: `HEAD` typically points to the latest commit.
 
**Index (Staging Area)**: A place where Git holds changes before they become a commit.

*Example*: Files added with `git add` go to the index.

**Init**: Creates a new Git repository.

*Example*: `git init new-repo`

**Log**: Displays the chronological commit history for a repository.

*Example*: `git log`

**Merge**: Integrating changes from one branch into another.

*Example*: `git merge feature-branch`

**Merge Base**: The most recent common ancestor of two branches.

*Example*: Found using `git merge-base branch1 branch2`

**Merge Conflict**: A disagreement between changes in different branches.

*Example*: Occurs during `git merge` and requires manual resolution.

**Pull**: Fetching changes from a remote repository and merging them into your local branch.

*Example*: `git pull origin main`

**Pull Request (PR)**: A request to merge your changes into another branch, usually in a remote repository.

*Example*: Done via GitHub's interface after pushing a branch.

**Push**: Sending your local changes to a remote repository.

 *Example*: `git push origin main`

**Rebase**: Sequentially applying changes from one branch to another.

 *Example*: `git rebase main`

**Remote**: A version of your repository hosted on a network, used for sharing.

 *Example*: List remotes with `git remote -v`.

**Remote-tracking Branch**: A reference to the state of branches in a remote repository.

*Example*: `origin/main` is a remote-tracking branch.

**Repository (Repo)**: A database storing the history of all changes made to a project. It can be local (on your machine) or remote (like on GitHub).

*Example*: Initialize a new repository with `git init`.

**Stash**: Temporarily saving changes without committing them.

*Example*: `git stash`

**Status**: Displays the state of the working directory and staging area.

*Example*: `git status`

**Submodule**: Embedding a repository within another repository.

*Example*: Adding a submodule with `git submodule add https://github.com/user/repo.git`

**Tag**: Marking specific points in a repository’s history.

*Example*: `git tag v1.0.0`

<div style="page-break-after: always; break-after: page;"></div>
