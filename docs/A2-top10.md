# Top 10 Most Commonly Used Git Commands

Here are the top 10 Git commands that you'll likely use right away. You already know most of these.

**git add**

Adds changes in the working directory to the staging area. It tells Git that you want to include updates to a particular file(s) in the next commit. However, `git add` doesn't affect the repository in any significant way—changes are not actually recorded until you run `git commit`.

Example: `git add .` (to add all changes) or `git add filename.txt` (to add a specific file)

**git branch**

Lists, creates, or deletes branches. It doesn't let you switch between branches or put a forked history back together. For that, you'll need `git checkout` or `git merge`.

Example: `git branch` (to list branches) or `git branch new-branch` (to create a new branch)

**git checkout**

Switches branches or restores working tree files. It is a way to select which line of development you’re working on.

Example: `git checkout new-branch`

**git clone**

Creates a copy of a target repository. This command is used to download the repository from an external source and initializes a new repository in the local environment, copying all the files, branches, and commits.
 
Example: `git clone https://github.com/username/repository.git`

**git commit**

Captures a snapshot of the project's currently staged changes. Commits can be considered as 'safe' versions of a project—Git will never change them unless you explicitly ask it to.

Example: `git commit -m "Add feature X"`

**git init**

Initializes a new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

Example: `git init`

**git merge**

Combines two branches together. `git merge` will take the changes from one branch (in the same repository or from a fork) and apply them into another. This often happens as a 'pull request' in GitHub, which can be done via the command line as well.

Example: `git merge new-branch`

**git pull**

Fetches the changes from the remote repository and merges them into the local repository. This command is a combination of `git fetch` and `git merge`, where `git pull` first updates the local remote-tracking branches, and then merges the changes from the remote main branch to your local branch.
 
Example: `git pull origin main`

**git push**

Updates the remote repository with any commits made on the local branch. If you're working on a shared repository, `git push` is how you transfer commits from your local repository to the remote repo.
 
Example: `git push origin main`

**git status**
Displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.
 
Example: `git status`

<div style="page-break-after: always; break-after: page;"></div>
