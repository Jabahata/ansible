yum install -y git - install git package
git config --global user.name “Jabahata” - set username for git as Jabahata
git config --globar user.email “email@gmail.com” - set email for git
git config --list - displays git configurations such as username and email
git config --global credential.helper cache - next time you pushed to use login and password it saves in cache
git push - then it will ask for username and password (personal token)
git config --global --unset credential.helper - remove credentials from cache
git remote set-url origin https://yourusername:yourtoken@github.com/yourusername/yourrepository.git - set up your toket for origin
To run any git command in Linux server you must be located in Git repository otherwise command will not work.
git add * - adding to git every changes has been made
git add --all - adding every changes even deleted ones
git status - check the status for any changes
git diff - displays conflicted files and their content
git add README.md - adding to git only README.md file
git commit -m “test” -  committing new changes and making comment of “test”
git push - push everything to Github.com
git branch - displays current working branch
git branch feature - creates feature branch
git branch -d feature - deletes feature branch
git checkout testbranch - switch from current branch to testbranch
git merge testbranch - merges changes from testbranch into the current branch
git pull origin main - Fetches changes from Github.com and merges them into the current branch
git log - displays log file for commits
git log --oneline - displays log file for commits in compact form
git config --global user.email “pipecday@gmail.com” - setting email
git config --global user.name “jabahata” - setting username
git remote -v - displays remote repositories and their URLs
git rm must_have.txt - deletes must_have.txt if file exists in github but not in the server
