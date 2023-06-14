# GitCommands

//Basics:

`git init`                         // to initialize the git repository

`git status`                        // to get the status of the repository

`git add .`                        // to stage all the files

`git add name`                     // to add  a specific file

`git restore --staged <file>`     // unstage the staged files

`git commit -m "message"`        // to commit the changes

`git log`                        // overall history

`git config --local credential.helper ""`    // any account already logged in
`git config --global --unset-all user.name`
`git config --global --unset-all user.email`



`git config pull.rebase false`      // Fix unrelated history
`git pull origin main`
