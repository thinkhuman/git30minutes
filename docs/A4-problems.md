# 10 Most Common Git Problems (and How To Resolve Them)

1.  **Problem: Merge Conflicts**

    *   **Solution**: When you get a merge conflict, Git will tell you which files are in conflict. Open these files and look for the lines that Git has marked with `<<<<<<<`, `=======`, and `>>>>>>>`. These markers separate the conflicting changes. Manually combine the changes, then `add` and `commit` the resolved files.

2.  **Problem: Committing to the Wrong Branch**

    *   **Solution**: If you've accidentally committed to the wrong branch, you can undo this by switching to the correct branch and using `git cherry-pick` to apply the commit. Then, go back to the wrong branch and use `git reset --hard HEAD~1` to remove the last commit.

3.  **Problem: Forgot to Add Files to a Commit**

    *   **Solution**: If you forgot to add some files to your last commit, add the files with `git add` and then use `git commit --amend`. This will let you update the previous commit with the new changes.

4.  **Problem: Pushing Fails due to Remote Changes**

    *   **Solution**: If `git push` fails because there are remote changes you don’t have, first use `git pull` to merge those changes into your local branch. Then you can push your changes after resolving any conflicts.

5.  **Problem: Lost Commits or Branches**

    *   **Solution**: If you've lost track of a commit or branch, use `git reflog` to find it. The reflog is a log of everything you've done in Git, and you can often find your lost commits there.

6.  **Problem: Accidentally Deleted a Commit**

    *   **Solution**: If you've deleted a commit by accident, `git reflog` is again your friend. Find the commit in the reflog and use `git checkout` to move to it, or use `git reset --hard commit_sha` to restore your branch to that commit.

7.  **Problem: Reverting a Commit**

    *   **Solution**: To undo a commit that has already been pushed, use `git revert commit_sha`. This will create a new commit that undoes the changes.

8.  **Problem: Removing Untracked Files**

    *   **Solution**: To clean your working directory from untracked files, use `git clean`. Be careful with this command because it will delete files from your disk. You can use `git clean -n` to do a dry run and see which files would be deleted.

9.  **Problem: Git Repository is Too Large**

    *   **Solution**: If your repository is too large, it might be because of large files. You can find large files with `git lfs (Large File Storage)` or rewrite history to remove them completely with `git filter-branch`. Make sure to back up your repository before doing this.

10. **Problem: Forgot to Ignore Files**

    *   **Solution**: If you forgot to ignore files and they've already been added to the repository, first add them to your `.gitignore` file. Then, use `git rm --cached` to remove them from the repository without deleting them from your local filesystem.

    <div style="page-break-after: always; break-after: page;"></div>
