# Step 5: Collaborate with Remote Repositories

Remember, a *repository* is just a collection of project files. That repository could be on your local drive, on a cloud service (like Dropbox), or a specialized service like [Github](https://github.com/). Github is a website where individuals and groups can share a repository (publicly or privately). A repository that isn't on your local drive is commonly called a *remote*.

**Why a remote repository?** 

There are two key reasons for having a remote repository like Github: 

1. You can store your project in a place that can be accessed from any computer where you have installed Git,
2. For collaboration. Once you have a remote repository, you can easily collaborate and share changes with other people.

**About 'pushing' and 'pulling'**: Commiting changes to a remote repository is called *pushing* the changes. Getting changes from a remove repository is called *pulling* the changes. 

We're going to use Github to set up a remote repository where you can push and pull changes. 

**A: Sign up for  a Github account**

**NOTE**: If you already have a Github account, you can skip this part.

1.  **Visit the GitHub Website**: Go to [GitHub's website](https://github.com/).
2.  **Sign Up**: Click on the “Sign up” button, usually located at the top right corner.
3.  **Enter Your Details**: Fill in your email address, create a username, and set a password.
4.  **Verify Account**: Follow any verification steps required by GitHub.
5.  **Choose a Plan**: Select a plan. You can start with the free plan, which is sufficient for most individual projects.
6.  **Complete Setup**: Complete any additional steps required by GitHub to set up your account.

**B: Create a new repository on Github**

1.  **Log In to GitHub**: Sign in to your GitHub account.
2.  **Go to Repositories**: Click on the “Repositories” tab.
3.  **New Repository**: Click the “New” button, usually located near the top right.
4.  **Repository Name**: Give your repository a name that reflects your project.
5.  **Initialize with README (Optional)**: You can choose to initialize your repository with a README file.
6.  **Create Repository**: Click on “Create repository.”

**C: Connect to a Remote Repository**

You have to connect your local and remore repositories before you can use the remote.

Link your local repository to the GitHub repository by adding the remote repository information:

`git remote add origin https://github.com/yourusername/your-repo-name.git`

**NOTE**: You'll find the actual URL on the Github page of your remote project. 

**D: Push to GitHub**

Push your commits to GitHub:

`git push -u origin master` 

(for the first push; later, you can simply use `git push`)

Your local and remote repositories are now connected; you can now work locally, and push changes to the remote whenever you like.

**E: Verify the Push**

Go back to your repository on the GitHub website, and refresh the page. Your files should now be visible there.

**F: Pull Changes**

Even though nothing has changed in the remote repository, let's practice *pulling* the latest changes from there:

`git pull origin main`

This will fetch the changes from the remote `main` branch and merge them into your local branch.

You now have the following:

* A local repository with Git version control
* A remote Github repository connected to your local one, where you can push and pull changes from


<div style="page-break-after: always; break-after: page;"></div>
