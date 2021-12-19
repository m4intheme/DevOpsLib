  A commit is an operation which sends the latest changes of the source code to the repository, making these changes part of the head revision of the repository.
 
 
To commit a change in git on the command line, assuming git is installed, the following command is run:
git commit -m 'commit message'

This is also assuming that the files within the current directory have been staged as such:
git add .

The above command adds all of the files in the working directory to be staged for the git commit. After the commit has been applied, the last step is to push the commit to the given software repository, in the case below named origin, to the branch master:
git push origin master

Also, a shortcut to add all the unstaged files and make a commit at the same time is:
git commit -a -m 'commit message'
