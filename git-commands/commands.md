<h3>Useful git commands</h3>
 - <b>git init </b> - For initializing git repository by creating a .git folder in the current directory where you run this command. You have to navigate to the directory where you want to initialize the git and then runt this command. Generally used when you start creating a new project.
 - <b>git clone </b> - For copying an exisiting project from remote to your local git repository. Usage : git clone {remote source url}
 - <b>git status</b> - Shows the untracked/changed files. Usage : git status
 - <b>git add </b> - For adding untracked/changed files to git index. Usage : git add {filename}
 - <b>git rm </b> - Remove the files from git index so they are not tracked. Usage : git rm {filename}
 - <b>git commit</b> - Commits all the changes that are added to index. Usage : git commit -m 'commit message'
 - <b>git branch</b> - Lists out the current branches available. -a option will list out the remote branches as well. Giving a name will actually create a branch. Usage : git branch -a 
 - <b>git checkout</b> - Will checkout a different branch in local by updating index, working tree and head to point new branch. Usage : git checkout {branch-name}
 - <b>git push</b> - Pushes all commited changes to remote branch. Usage : git push -u origin master
