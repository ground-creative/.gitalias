# A collection of shortcuts for git

## Installation

Download the file to your  local repository
```
wget https://raw.githubusercontent.com/ground-creative/.gitalias/main/.gitalias
```

Add the following 2 lines to your .git/config file
```
[include]
	path = ../.gitalias
```

## Shortcuts list

| Command  | Explanation |
| ------------- | ------------- |
| git current | *get current branch* |
| git rebuild-tags  | rebuild local tags from remote  |
| git list-alias  | show list of alias  |
| git last-com | show last commit  |
| git unchanged | assumed unchanged |
| git no-unchanged  | reverse assumed unchanged  |
| git list-branches  | list all branches  |
| git show-com  | *show list of commits, params: number of commits (optional)* |
| git show-com  | *reset commit, params: commit id (optional, the last id will be used if empty)* |
| git com-all | *add and commit all changes, params: commit message (opional, the last commit will be used if not set)* |