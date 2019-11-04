### Getting & Creating Projects

`git init`  Initialize a local Git repository

`git clone ssh://git@github.com/[username]/[repository-name].git` Create a local copy of a remote repository 

### Basic Snapshotting

`git status` Check status 

`git add . ` Add all new and changed files to the staging area 

`git commit -m "[commit message]"`  Commit changes 

`git push origin master` push the staged,commited code to master branch.

…or create a new repository on the command line

`echo "# Title" >> README.md
 git init
 git add README.md
 git commit -m "first commit"
 git remote add origin https://github.com/onFilm/jenkinsDemo.git
 git push -u origin master`

…or push an existing repository from the command line
`git remote add origin https://github.com/onFilm/jenkinsDemo.git
 git push -u origin master`
