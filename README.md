echo "# new-project" >> README.md
# at root of local codebase
> git init
> git add --all
> git commit -m 'First commit'
> git branch -M main

# copy the remote repository URL
> git remote add origin <remote repository URL>
	
# set the new remote
> git remote -v

# now push as you normally would
> git push -u origin main
> 
# create a new branch and change branch
> git branch development
> git checkout development
