Dev Goodies
===========

Collections of utility scripts for Bash and Git.

We find these scripts useful when developing our products. Hopefuly you'll
find them useful, too!

Here's what we have to offer:


Git scripts
-----------

* `bin/git-cherry-files`:
  Similar to `git cherry-pick`, but lets you specify just the files you want
  from the commit.

* `bin/git-hatchet`:
  Takes a commit on a branch and chops it up into multiple commits across
  multiple branches, based on file paths.

* `bin/git-integrate`:
  Rebases another branch onto your current branch, merges it in, and deletes
  the old branch. Useful for cleanly bringing in changes in your local-only
  feature branch.

* `bin/git-j`:
  A faster, easier, and more powerful way to navigate between branches in Git.

* `bin/git-rebase-chain`:
  Like `git rebase`, but handles rebasing lines of branches all in one go,
  safely.

* `bin/git-stage-branch`:
  Creates a staged branch containing a single commit, based on a tree full
  of commits.

* `dotfiles/gitconfig`:
  A series of aliases useful for Git, especially in conjunction with our
  other handy Git scripts.


Other scripts
-------------

* `bin/find-unused-c-includes`:
  Finds all `#include` statements in C/C++ files that are no longer needed.

* `bin/pywhere`:
  Displays the path to the named Python module.

* `bin/wpatch`:
  Applies a patch stored on a remote HTTP server.
