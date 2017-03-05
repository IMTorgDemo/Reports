# Reports

Instructional reports and guides for supporting [ScrumSaga](www.scrumsaga.com).



# Remove commit history
This should be performed to ensure password information is not left in the reports.  Use the following steps:

1. Checkout

    git checkout --orphan latest_branch

2. Add all the files

    git add -A

3. Commit the changes

    git commit -am "commit message"

4. Delete the branch

    git branch -D master

5. Rename the current branch to master

    git branch -m master

6. Finally, force update your repository

    git push -f origin master
