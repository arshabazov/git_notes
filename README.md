# Git notes

### Initiating git for tracking local project
1. cd to project folder && run command: ~~~git init~~~
2. Track project files by added them to the staged area of git: ~~~git add~~~
3. Commit local changes: ~~~git commit -m "Comment"~~~ where -m flag stands for comment

### Create and linking repository on local machine with GitUub account:
1. Create an empty repository on GitHub
2. Link the remote repository with local on machine on: ~~~git remote ad origin git@github.com:account_name/project_name.git~~~
3. Check that the connection was successful: ~~~git remote -v~~~
4. Synchronise the tow repositories: ~~~git push -u origin main~~~  where orgin is name of the remote reposity, and main is the name of the current branch
5. For further sybchronisation between the two repositories: ~~~git push~~~
