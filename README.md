Easy way to create a Portfolio:
First get the github user name and password 
Second click on the New button
Next give the repository name(Portfolio), make it public and add a readme file, click on create repository. Hence your repository is created.

Now get the repository from the github to the system on which your are working
To achieve that,go to the working folder(ex:documents folder) where you want to get the repository folder.
Use the command cd Documents/ in the terminal to go inside the folder through the terminal
To confirm the git software installed in your system use the git command 
Prior to clone the repository to the system,copy the HTTPS LINK under the code button inside the repository page in github.
Now get the repository to the system by using the git clone command in the terminal. 
Use this git clone command git clone https://github.com/haseenasyed7/Portfolio.git in the terminal.Wait till the git gets cloned into the system .
To confirm the folder is created or not, use the ls command.Once you see the repository name hence it is confirmed.
After that go inside the repository folder that is created inside the system using cd repository name(cd Portfolio)
Now use the ls command. You can see the readme file.
Then create a file with the command touch file name (ex: touch index.html)
Use the ls command to check whether the file is created.
After that use the git status command to check the current status of the working folder(Portfolio) and the staging area.
Later you can see the untracked files in the red color i.e., index.html 
In order to send the index.html to the staging area use git add filename i.e.,(git add index.html)
Then after use the git status command to check the status of the file, green color confirms that the file has been staged
Later use the git commit command to commit the changes in the staging area(git commit -m "write any message")
Use git push origin main command to push the chages to the github. This commands shows the changes in the github 
Give the username and password asked by the push command
To get the push command password, go to the profile -> settings -> Developer settings -> Personal access token -> Token Classic -> create new token -> Generate new personal access token (classic) -> write a note and give expiry date -> check the repo checkbox -> click on generate token. Hence the new token is generated copy and save it for the future use. The generated token can be used as password for the push command.
Now use git pull origin main command to pull the changes made in the readmefile diectly in the github to the system where you are working(Portfolio folder)