# cli commands for git, linux and more

## linux

		man <any-command-or-program> # to check it's manual

		sudo apt-get install <app-name>

## git

		git clone <repo-url> # clones remote repository into a local repository

		git checkout <branch-name> # switches to another branch

		git checkout -b <new-branch-name> # copies current branch to a new branch

		git branch # checks current branch. -vv for verbose

		git add -A # adds files to commit. -A flag to add all modified files
		
		git commit -m "commit message" # commits your changes

		git push # pushes your changes to current branch

		git pull # updates your branch with remote

		git pull --rebase origin dev # updates current branch with any other branch. In this case, origin/dev
		git log # registros de alterações
## work routine

* git pull --rebase origin dev # updates current branch with any other branch. In this case, origin/dev

* make your changes

* git add -A

* git commit -m "commit message"

* git pull --rebase origin dev # again, with working simutaneously

* git push
