# GitCommands

## Table of Contents
- [Some Commands](#commands)
- [Usage](#usage)
- [Contributing](#contributing)

## Commands

`git log`                        // overall history

`git config --local credential.helper ""`    // any account already logged in

`git config --global --unset-all user.name`

`git config --global --unset-all user.email`



`git config pull.rebase false`      // Fix unrelated history

`git pull origin main`

`git push origin main`



## Usage

| Command                    | Description                                |
| -------------------------- | ------------------------------------------ |
| `git init`                 | Initialize the git repository              |
| `git status`               | Get the status of the repository           |
| `git add .`                | Stage all the files                        |
| `git add <name>`           | Add a specific file                         |
| `git restore --staged <file>` | Unstage the staged files                  |
| `git commit -m "message"`  | Commit the changes                          |


| Command                    | Description                                |
| -------------------------- | ------------------------------------------ |
| `git log`                  | View the overall history of the repository  |
| `git config --local credential.helper ""` | Configure local credential helper |
| `git config --global --unset-all user.name` | Unset global user name |
| `git config --global --unset-all user.email` | Unset global user email |
| `git config pull.rebase false` | Fix unrelated history |
| `git pull origin main`     | Pull the latest changes from the remote repository |
| `git branch`               | List all the branches in the repository     |
| `git checkout <branch>`    | Switch to a different branch                |
| `git merge <branch>`       | Merge changes from a different branch       |
| `git pull`                 | Fetch and merge remote changes               |
| `git push <remote> <branch>` | Push local commits to a remote repository  |
| `git remote add <name> <url>` | Add a remote repository                    |
| `git remote -v`            | List all remote repositories                |
| `git fetch`                | Retrieve the latest changes from a remote repository |
| `git reset <file>`         | Unstage a file, removing it from the staging area |
| `git revert <commit>`      | Create a new commit that undoes changes made in a previous commit |
| `git stash`                | Temporarily save changes without committing  |
| `git tag`                  | List or create tags for marking specific points in the commit history |
| `git remote show <remote>` | Show detailed information about a remote repository |

## Contributing

Contributions are welcome! If you have any ideas or suggestions, please open an issue or submit a pull request.

