## Git and Github interview questions

1. > What is the difference between git pull and git fetch ?

**Answer** :
Git pull and git fetch are both Git commands used to update a local repository with changes from a remote repository. However, there are differences between them:

1. Git Fetch:
    - The git fetch command retrieves new commits, branches, and tags from a remote repository without modifying the local branch.
    - It updates the remote-tracking branches (e.g., origin/master) to reflect the latest state of the remote repository.
    - Fetching allows you to see the changes made by others without merging them into your local branch.
    - After fetching, you can compare the fetched branch with your local branch and decide whether to merge the changes.

2. Git Pull:
    - The git pull command fetches the changes from the remote repository (similar to git fetch) and automatically merges them into the current local branch.
    - It is essentially a combination of git fetch followed by git merge to bring the remote changes into the local branch.
    - If there are no conflicts between the remote and local branches, git pull will perform a fast-forward merge. Otherwise, it may result in a merge commit.

**In summary, the main differences between git pull and git fetch are:**

- "git fetch" updates the remote-tracking branches without modifying the local branch, allowing you to review the changes before merging them.
- "git pull" fetches the changes and automatically merges them into the current local branch.
- "git pull" is more convenient for quickly updating the local branch, but git fetch provides more control and visibility over the changes before merging.
