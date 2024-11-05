 # Git & Github Command 

## Git Configuration

- <b> To See Git Version :</b>  git –version
- <b>To see git user name & email :</b> git config --list
- <b>To see git user name :</b> git config user.name
- <b>To see git user email:</b> git config user.email
- <b>To set git user name:</b> git config --global user.name "Khan-Jahan"
- <b>To set git user email:</b> git config --global user.name "Khan-Jahan

## Git Initialized & Staging 
- <b> To Initialized the file:</b> git init
- <b> Working Directory to Staging area: </b> git add.
- <b> Staging area to local repository: </b> git add commit -m "Message"
- <b> 24.	For staging and moving to local repository by once command : </b> git add . && commit -m “message”
- <b> Open the repository to Github:</b> Create a new repository
- <b> Connect to local repository by url
- <b> File push to local repository to Remote repository :</b> git push

## Connecting Local with Remote repository
- <b> To check connection of repository :</b> git remote -v
- <b> Connecting Local with Remote repository :</b> git remote add name "Write https URL"
- <b> To Pull the remote repository in divice :</b> git pull "Write https URL"
- <b> To Push the remote repository :</b> git push "Write https URL"
## Moving Backward.
- <b> Commited File move To staging area:</b> git reset --soft head^
- <b> Staging File move To unstage area :</b> git rm --cached test.md