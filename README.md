# dsci-310-tutorial-2

- `git branch`: Return all branches in the repository
- `git branch <BRANCH>`: Create `<BRANCH>` if it does not exist (will return error if it does)
- `git switch <BRANCH>`: Switch active branch to `<BRANCH>`
- `git log`: View the version control history
- `git log --oneline`: View the version control history, but only the commit message
- `git log --oneline --graph`: Graphic view of version control history between branches; only shows latest commit
- `git log --oneline --graph --all`: Graphic view of version control history between branches; shows all commits

- Branch: Separate version of the "main" repository, allowing for an "alternate timeline" to be created, so merge conflicts are reduced. (https://www.w3schools.com/git/git_branch.asp?remote=github)
- Pull request: Proposal to merge a set of changes from one branch into another. (https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

- `git push <WHERE> <WHAT>`: Push changes from the local version control repository to the <WHERE> repository on GitHub.com for branch <WHAT>
- `git pull <WHERE> <WHAT>`: Pull changes from the <WHERE> version control repository on GitHub.com to the local repository for branch <WHAT>
