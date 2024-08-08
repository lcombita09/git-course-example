# Example GIT Repository.

We are learning how to make commits with the CLI.

1. make some changes
2. git add-- "stage" the changes that we want to persist to our git history.
3. git commit -m "inster a clear message with the changes we want to commit" -- creates a commit.

# Cerate a branch locally.
git checkout <branch> main or master
git checkout -b <new branch>
git add...; git commit -m "..."(several items)
git --push --set-upstream origin <new branch>. What --set-upstream origin do is basicly connects the local branch to the cloud one.
git pull

# Create a branch remotely.
Using the Github UI to create <branch>
git fetch --all
git checkout <branch>