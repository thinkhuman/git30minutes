# Example Scenario Using All 10 Commands

Imagine you are starting a new project called "MyProject":

1.  You initialize the project with Git:

    `git init MyProject`
    `cd MyProject`

2. After working on your project, you decide to push it to a remote repository so your team can work on it. First, you clone a starter repository that your team agreed on:

    `git clone https://github.com/username/starter-repo.git`

3. You add a file you just created called `README.md`:

   `git add README.md`

4. You commit your changes with a message describing what you've added:

    `git commit -m "Initial commit with README"`

5. To ensure you’re ready to push your changes, you check the status:

    `git status`

6. You push your commit to the newly cloned repository:

    `git push origin main`

7. Your teammate has made changes to the repository, so you pull the latest changes from the remote repository:

    `git pull origin main`

8. You need to work on a new feature, so you create a new branch called "feature-x":

    `git branch feature-x`

9. You switch to the new branch to start working on it:

    `git checkout feature-x`

10. After completing work on "feature-x", you switch back to the main branch and merge the changes from "feature-x" into "main":

    `git checkout main`
    `git merge feature-x`

<div style="page-break-after: always; break-after: page;"></div>
