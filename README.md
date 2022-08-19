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

### Make Alias
- `alias gc="git commit"`

### Git Update
```
sudo add-apt-repository ppa:git-core/ppa -y
sudo apt-get update
sudo apt-get install git -y
git --version
```

### Credential Store
```
git config credential.helper store
```

### Git Config
There are 3 levels of git config; project, global and system: 

- project: Project configs are only available for the current project and stored in .git/config in the project's directory.

- global: Global configs are available for all projects for the current user and stored in ~/.gitconfig.

- system: System configs are available for all the users/projects and stored in /etc/gitconfig.


Create a project specific config, you have to execute this under the project's directory:
```
git config user.name "John Doe"
git config user.email "johndoe@example.com"
```

Create a global config:
```
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
```

Create a system config:
```
git config --system user.name "John Doe"
git config --system user.email "johndoe@example.com"
```