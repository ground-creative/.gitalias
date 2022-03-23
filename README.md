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
| git rebuild-tags  | *rebuild local tags from remote* |
| git list-alias  | *show list of alias*  |
| git last-com | *show last commit*  |
| git unchanged | *assumed unchanged* |
| git no-unchanged | *reverse assumed unchanged* |
| git list-branches  | *list all branches*  |
| git show-com  | *show list of commits<br>params: number of commits (optional)* |
| git uncom  | *reset commit<br>params: commit id (optional, the last id will be used if empty)* |
| git com-all | *add and commit all changes<br>params: commit message (opional, the last commit will be used if not set)* |
| git push-all | *add, commit and push all changes<br>params: commit message (opional, the last commit will be used if not set)* |
| git show-cmd | *show config details<br>examples: "git show-cmd" "git show-cmd alias" "git show-cmd alias push"* |
| git update-release  | *update latest release files from current branch*  |
| git upgrade-script  | *upgrade the script*  |