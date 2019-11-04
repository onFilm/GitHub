### Getting & Creating Projects
`git init`  Initialize a local Git repository <br />
`git clone ssh://git@github.com/[username]/[repository-name].git` Create a local copy of a remote repository 

### Basic Snapshotting
`git status` Check status <br />
`git add . ` Add all new and changed files to the staging area <br />
`git commit -m "[commit message]"`  Commit changes <br />
`git push origin master` push the staged,commited code to master branch.<br />

…or create a new repository on the command line<br />
`echo "# Title" >> README.md`<br />
`git init`<br />
`git add README.md`<br />
`git commit -m "first commit"`<br />
`git remote add origin https://github.com/onFilm/jenkinsDemo.git`<br />
`git push -u origin master`<br />

…or push an existing repository from the command line<br />
`git remote add origin https://github.com/onFilm/jenkinsDemo.git`<br />
`git push -u origin master`<br />
