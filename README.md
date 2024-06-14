# git add
The git add command adds content from the working directory into the staging area (or “index”) for the next commit. When the git commit command is run, by default it only looks at this staging area, so git add is used to craft what exactly you would like your next commit snapshot to look like.

This command is an incredibly important command in Git and is mentioned or used dozens of times in this book. We’ll quickly cover some of the unique uses that can be found.

We first introduce and explain git add in detail in Tracking New Files.

We mention how to use it to resolve merge conflicts in Basic Merge Conflicts.

We go over using it to interactively stage only specific parts of a modified file in Interactive Staging.

Finally, we emulate it at a low level in Tree Objects, so you can get an idea of what it’s doing behind the scenes.

# git status
The git status command will show you the different states of files in your working directory and staging area. Which files are modified and unstaged and which are staged but not yet committed. In its normal form, it also will show you some basic hints on how to move files between these stages.

We first cover status in Checking the Status of Your Files, both in its basic and simplified forms. While we use it throughout the book, pretty much everything you can do with the git status command is covered there.

# git commit
The git commit command takes all the file contents that have been staged with git add and records a new permanent snapshot in the database and then moves the branch pointer on the current branch up to it.

We first cover the basics of committing in Committing Your Changes. There we also demonstrate how to use the -a flag to skip the git add step in daily workflows and how to use the -m flag to pass a commit message in on the command line instead of firing up an editor.

In Undoing Things we cover using the --amend option to redo the most recent commit.

In Branches in a Nutshell, we go into much more detail about what git commit does and why it does it like that.

We looked at how to sign commits cryptographically with the -S flag in Signing Commits.

Finally, we take a look at what the git commit command does in the background and how it’s actually implemented in Commit Objects.
