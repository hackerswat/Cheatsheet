# Git Commands Cheat Sheet

This README provides a cheat sheet for commonly used Git commands with brief explanations.

## Basics

1. `git init`: Initializes a new Git repository in the current directory.

2. `git clone <remote_repository_url>`: Creates a local copy of a remote repository.

3. `git status`: Shows the current status of your working directory and staging area.

4. `git log`: Displays the commit history.

5. `git diff`: Shows the differences between the working directory and the staging area or the last commit.

6. `git add .`: Adds all changes to the staging area. Use `git add <file>` for specific files.

7. `git commit -m "Commit message"`: Creates a new commit with the staged changes.

8. `git push <remote_name> <branch_name>`: Pushes committed changes to a remote repository.

9. `git pull <remote_name> <branch_name>`: Fetches and merges changes from a remote repository.

10. `git remote -v`: Lists remote repositories and their URLs.

## Branching and Merging

11. `git branch`: Lists existing branches. Use `git branch <new_branch_name>` to create a new branch.

12. `git checkout <branch_name>`: Switches to an existing branch. Use `git checkout -b <new_branch_name>` to create and switch to a new branch.

13. `git merge <branch_name>`: Merges changes from another branch into the current branch.

14. `git remote show <remote_name>`: Provides detailed information about a remote repository.

15. `git tag`: Lists all tags. Use `git tag -a <tag_name> -m "Tag message"` to create an annotated tag.

## Undoing Changes

16. `git reset HEAD~1`: Undoes the last commit but keeps changes in the working directory.

17. `git reset --hard <commit_hash>`: Resets the current branch to a specific commit. **Use with caution**.

18. `git revert <commit_hash>`: Creates a new commit that undoes changes introduced by a specific commit.

19. `git stash`: Temporarily saves changes that are not ready to be committed.

20. `git clean -d`: Removes untracked files from the working directory.

## Miscellaneous

21. `git fetch <remote_name>`: Downloads objects and refs from a remote repository without automatically merging them.

22. `git remote add <remote_name> <remote_repository_url>`: Adds a new remote repository.

23. `git remote remove <remote_name>`: Removes a remote repository.

24. `git add .`: Adds all changes to the staging area.

25. `git push <remote_name> <tag_name>`: Pushes a tag to the remote repository.

26. `git stash pop`: Applies the most recent stash and removes it from the stash list.

27. `git stash apply stash@{<stash_index>}`: Applies a specific stash and removes it from the stash list.

28. `git cherry-pick <commit_hash>`: Applies changes from a specific commit to the current branch
