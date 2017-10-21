# kedroskiwedding
wedding repository

## Usage

```
git init
git remote add origin git@bitbucket.org:Avionos/pdc.git
git pull origin master
```

### Git Commands

#### Show the local changes that have been made / current branch
```git status```

#### Add the file(s) to the index staged for the next commit
```git add <file>```

#### Record the changes to the repository
```git commit -m 'commit message'```

#### Push the recorded changes to the repository
```git push origin <branch-name>```

#### Undo last commit - Will reset the last commit and leave changes unstaged
```git reset HEAD~```

#### Undo last commit - Will reset the last commit and leave changes staged
```git reset --soft HEAD~```

#### Pull any changes to the repository into your local master branch
```git checkout master```

```git fetch origin```

```git merge origin/master```

#### Pull any changes to a local branch after updating master
```git checkout <branch>```

```git merge master```

#### List local branches
```git branch --list```

#### Remove local branch
```git branch -D branch-to-delete```