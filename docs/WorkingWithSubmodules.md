Key Update Scenarios

Track Latest Remote Commits: Use `git submodule update --remote` to pull new
commits into the main repository and its submodules, changing working
directories to the commit of the tracked branch. 

Reset to Parent Commit: Running `git submodule update without --remote` checks
out the specific revision referenced in the parent repository, useful for
restoring a submodule to a known state. 

Preserve Local Changes: If you have uncommitted work, you can stash it with git
submodule foreach `git stash`, update with `git submodule update --remote`, and
restore changes with git submodule foreach 'git stash pop'. 

Merge or Rebase: Use `git submodule update --remote --merge` to merge remote
changes or `--rebase` to replay local commits on top of updated remote branches. 

Sync URLs: If a submodule's remote URL changes, run `git submodule sync
--recursive` before updating to ensure the local configuration matches the
`.gitmodules` file.
