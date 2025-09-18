# Step 2: Make Your First Commit

A _commit_ is a record of the changes you've made to files that are in your Git repository. 

Think of making a commit as saving your work with a note (a 'commit message') about what you did, and why. 

Git gives each commit you make a special code (a unique 40-character string called a 'hash') so you can find it later if you need to. You'll sometimes use this special code to 'revert' to a previous version of one or more files, or to share with other people.

**A: Create Your First Project File**

In the `example-project` directory, create a new file named `README.md`.

* On Unix-based systems like MacOS or Linux, you can use `touch README.md`.
* On Windows, create a new text file and rename it to `README.md`.

**B: Stage Changes**

_Staging_ is the preliminary step where you prepare and organize your changes before committing them to the Git repository. 

Think of staging as packing a box for delivery. You decide which items (changes) you want to send off (commit), and you put them in the box (staging). Once you're happy with what's in the box, you seal it and send it (commit the changes). This allows you to choose which changes to commit, which becomes more important when you have multiple files.

In the `example-project` directory, stage the new file for commit:

`git add README.md`

Git is now tracking changes made to `README.md`.

**C: Commit Your Changes**

Now, your changes are staged and ready to be commited to the Git repository.

In the `example-project` directory, commit your staged files:

`git commit -m "Initial commit with README"`

Here's how that command works:

1.  **`git commit`**: The Git command to save changes to the local repository. 
2.  **`-m`**: An option (often called a 'flag') for the `git commit` command. The `-m` stands for "message", which just means "I'm adding a commit message right after this".
3.  **`"Initial commit with README"`**: The commit message that you're including with the `-m` option. 

  **NOTE**: Commit messages should be descriptive, so you (and others) can easily understand what changes were made. This becomes more important as you create several versions over longer periods of time, and forget what changes were made.

<div style="page-break-after: always; break-after: page;"></div>
