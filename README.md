# INTRODUCTION:
Git is a free open source version control system. It helps in tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

# TERMS:
1. Directory -> Folder
2. Terminal/Command line -> Interface for Text Commands
3. CLI -> Command Line Interface
4. cd -> Change Directory
5. Repository -> Project/Folder where the project is kept
6. Github -> A website to host your repos online

# Commands in Git:
1. Clone
2. Add
3. Commit
4. Push
5. Pull
   
# Code Commands:

## Pulling from GitHub TO Directory:
` git clone repo_link `

## Save changes to Git :
1. ` git status `
2. ` git add . `
 
## Commiting files: 
` git commit -m "any_msg" -m "description" `

## Push to remote repo:
` git push -u origin main `

## Compare codes:
` git diff `

## Branching:

### `Create new branch:
` git checkout -b branch_name `

### Switch among branches:
` git checkout branch_name `

### Push Branch:
` git push -u origin branch_name `

### Merge Branch:
` git merge branch_name `

## Undo Commit:
` git reset HEAD~how_many_commits_back `

## Commit Log:
` git log `

# Fork:
Used to get a copy of others repo into into our own repo.  Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.



