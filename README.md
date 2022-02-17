# git-assessment

## The Perfect Commit

$ git add -p index.html (add: To stage file /// -p: Decide what to include or not include)

$ git status (To check changes to be commited and/or changes not staged for commit)

$ git commit -m "" (Enter your message and commit the changes)

-   Subject = Summary of what happened
-   Body = Detailed explanation what has changed

$ git log (Check the commit messages)

---

## Branching Strategies "Always Be Integrating"

-   Few branches
-   Relatively small commits
-   High-quality testing

-   Long-Running Branches
    ~ Exist to complete lifetime of the project
    ~ Mirror stages in dev life cycle
    ~ No direct commits

-   Short-Lived Branches
    ~ For new features, bug fixes, etc
    ~ Will be deleted after merge

---

## Pull Request

-   Before Pull Request reviwers have to provide feedback, once it's done merge can be made

-   Forks: Are a personal copy from other repositories

---

## Merge Conflicts

-   When occur: git merge/rebase/pull/stash apply/cherry-pick and one line has 2 or more different changes

$ git merge/rebase --abort (--abort: Undo a conflic)

-   How to solve a conflict: Cleaning up the code or use GUI that can help you solve the conflict easier (personal prefered GUI: VSC GitLens)

-   Don't forget to commit after conflict has solved

---

## Merge vs Rebase

-   Merge
    ~ Simple and familiar.
    ~ Preserves complete history and chronological order.
    ~ Maintains the context of the branch.

-   Rebase
    ~ Avoids merge commit in repos with branches.
    ~ Cleans intermediate commits by making them a single commit

## ** Do NOT use Rebase on commits hat you've already pushed/shared on a remote repository **
