# Step 4: Branch Out

A _branch_ is a way to work separately on different parts of a project at the same time, without affecting the main project (often called the "master" or "main" branch). You can think of it as a parallel universe where you can make changes or try out new ideas and, when you're ready, bring those changes back into the main project.

In simple terms, imagine you're writing a story in a notebook. A branch is a separate copy of the notebook. In this copy, you (or someone else) can make changes, add new characters, or change the plot without messing up the original story. Later, if you like the changes, you can merge them into the main notebook (and Git helps you resolve any differences between the two notebooks). 

**A: Creating a New Branch**

In the `example-project` directory, create a new branch named `feature-x`:

 `git branch feature-x`

**B: Switching Branches**

Switching to another branch is called _checking out_ a branch. This just means you're leaving one branch to work on a different one.

Now, switch to the `feature-x` branch:

 `git checkout feature-x`

You've now moved to a new branch, where you can make changes without affecting the main branch.

**C: Merging Changes**

After making changes in the `feature-x` branch, merge those back into the main branch:

1. `git checkout main` (switch back to the original 'main' branch)
2. `git merge feature-x`

Now your main branch will have all the changes you made in your `feature-x` branch.

To see your changes, open the `README.md` file in a text editor. 

**Wait! Which Branch Am I On?**

To find out which branch you're on type the following command:

`git branch`

When you run this command, Git lists all the branches in your repository and puts an asterisk (*) next to the branch you're currently on. Remember: you can switch amongst different branches using `git checkout [branch name]`.


<div style="page-break-after: always; break-after: page;"></div>
