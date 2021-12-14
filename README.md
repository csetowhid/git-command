# Git Commands

### Stage All
- `git add --all`
- `git add -A`

### Clean Untracked File
- `git clean -f -n`
- `git clean -f`
### Stage All From Specific Folder
- `git add .`

### Stage All Without Deleted File 
- `git add *`

### Stage To Local
- `git reset`

### Commit Rollback
- `git reset HEAD~`

### Hard Rollback
- `git reset --hard`

### Rollback File
- `git checkout filename`

### Rollback Deleted File (All)
- `git checkout -f`

### Temporary Commit
- `git stash`

### Temporary Commit List
- `git stash list`
### Get Temporary Commit
- `git stash pop`

### Get Temporary Commit
- `git stash pop stash@{1}`

### Get Temporary Commit Clear
- `git stash clear`

### Git Ignore
- `app.js`
- `img/`
- `css/bootstrap.css`
- `*.jpg`
- `*.png`

### Force Commit

`git add .`\
`git commit --amend` \
`ctrl + o`\
`Enter`\
`ctrl + x`\
`git push origin <branch name> --force`
