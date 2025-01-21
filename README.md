# 2025-01-21 Branch Conflict

-   Last time we talked about branching.

-   Today we focus on something that'll be similar to what's to be expected in the project.

    -   Branches come from the same source, where the branches may or may not have conflicts.

-   (recall ls -a shows also the hidden files)

-   `git switch -c`, where c stands for 'create'.

    -   Instead of needing to run `git branch` and `git switch`.

    -   Keeping track of where `HEAD` is would be a crucial thing to know where your current position is with `git log —oneline`.

-   git switch -c <NAME> will create a new branch and switch to it.

-   "." stands for where I'm current at (e.g., when calling pwd)

    -   Take every file in your working directory and add them if you put a "." with `git add .`

        -   A shortcut way of adding everything in your current directory!

-   Having a .gitignore file can be useful because when you're merging two pull requests, you can be sure that the conflict is not due to some trivial temporary files.

2 Ways of Fixing Branch Conflict:

1.  Manual fix on Github interface remotely.
2.  Use command: `Rebase` and trigger a merge conflict locally:
    -   Move the b2 banch to the front of the main branch line.

    -   The question now is how to resolve this triggered merge conflict locally.
