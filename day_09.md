ctivity_9


Today i learn about git hub how push a local file into github folder.
git Hub CLI is an open source tool for using GitHub from your computers command line. GitHub CLI can simplify the process of adding an existing project to GitHub using the command line To learn more about GitHub CLI see About GitHub CLI
In the command line, navigate to the root directory of your project.
 Initialize the local directory as a Git repository.
 git init -b main
 Stage and commit all the files in your project
 git add and git commit -m initial commi
 To create a repository for your project on GitHub, use the gh repo create subcommnd. When prmpted. select Push an existing loal repository to GitHub and enter the desired name for your repository. If you want your project to belong to an organization instead of your user account, specify the organization name and project name with organization-name/project-name.
 Follow the interactive prompts. To add the remote and push the repositoy, confirm yes when asked to add the remote and push the commits to the current branch.Alteratiely to skip all the prompts, supply the path to the repository with the source flag and pass a visibility flag public privat, orinternal). For example gh repo creat rce=public. Specify a remote with the --remote flag. To push your commits, pass the --push flag. For more information about possible arguments, see the GitHub CLI manual.
Adding a project to GitHub without GitHub CL
Create a new repository on GitHub.com. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub. Create New Repository drop-dwnOpen Termina
Change the current working directory to your local project.Initialize the local directory as a Git repository
git init -b mainAdd the files in your new local repository. This stages them for the first commit.git add
adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE
caommit the files that you've staged in your local repository.
git commit -m First commit
Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset soft head and commit and add the file again.
At the top of your repository on GitHub.com's Quick Setup page, click 
to copy the remote repository URL. Copy remote repository URL field
In Terminal, add the URL for the remote repository where your local repository will be pushed.git remote add origin 
Sets the new remote.git remote -v
Verifies the new remote URL
Push the changes in your local repository to GitHub.com.
git push origin main
Pushes the changes in your local repository up to the remote repository you specified as the orgin.


