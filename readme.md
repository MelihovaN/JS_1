<h1 align="center">Git fetch vs Git pull</h1>

### Both commands are used to download new data from a remote repository.

### Downloading data is an essential step in the daily work - because the remote data you are looking at in your local repository is just a "snapshot". It's only as up-to-date as the last time you explicitly downloaded fresh data from the remote with "fetch" or "pull".

## Git fetch

**Git fetch** is the command that tells your local git to retrieve the latest meta-data info from the original (yet doesn’t do any file transferring. It’s more like just checking to see if there are any changes available).


## Git pull

**Git pull** is a command that allows you to fetch from and integrate with another repository or local branch.
**Git pull** is actually a Git fetch followed by an additional action(s)—typically a Git merge.



### The short definition **git fetch** just "downloads" the changes from the remote to your local repository. **Git pull** downloads the changes and merges them into your current branch.

---

<h1 align="center">Git commit --amend</h1>

The **git commit --amend** command is a convenient way to modify the most recent commit. It lets you combine staged changes with the previous commit instead of creating an entirely new commit. It can also be used to simply edit the previous commit message without changing its snapshot. But, amending does not just alter the most recent commit, it replaces it entirely, meaning the amended commit will be a new entity with its own ref. To Git, it will look like a brand new commit.

**git commit --amend -m" "** change most recent Git commit message. Adding the -m option allows you to pass in a new message from the command line without being prompted to open an editor.
