# Git Tag Syntax

This repository is a sample repository dedicated to assisting you with learning the core concepts of tagging with Git.

## Commands For Git Tagging

*   `git log`
    *   The command used to display the "commit history" of a git repository
    *   Appending the `--stat` option will also display the changes attached to each commit
    *   Appending the `--all` option will show all commits and branches
    *   Appending the `--graph` option will visually "graph" the relationship between commits with ASCII art
*   `git tag TAG_NAME [Commit]`
    *   Add a new git tag, titled `TAG_NAME`, to a given commit
    *   If the `[Commit]` option is not given, the tag gets added to the most recent commit
    *   If the `[Commit]` option is given, the tag gets added to the specified commit
    *   The `[Commit]` option can be a git hash or a relative reference to a commit
*   `git tag -d TAG_NAME ...`
    *   Deletes the git tag titled `TAG_NAME` from the *local* repository
    *   Can delete multiple tags at once by specifying multiple `TAG_NAME`'s in a single command
*   `git push remote TAG_NAME`
    *   Pushes the tag titled `TAG_NAME` to the specified `remote`
*   `git push -d remote TAG_NAME`
    *   Deletes the git tag titled `TAG_NAME` from the *remote* repository specified by `remote`
*   `git help tag`
    *   View `git help` information for the git's `tag` subcommand 

