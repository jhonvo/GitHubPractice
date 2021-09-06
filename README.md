<h1>Main Commands</h1>
<br><br>
<h2>Folder and files navigation...</h2>
<br><br>
ls - Shows everything under the current section we are on 
<br>
cd - Change to another directory 
<br>
cd .. - Go up one directory 
<br>
mkdir - Creates a new folder 
<br>
touch - Creates a new file 
<br>
rm - Removes a folder or file
<br>
<br>
<h2>Git commands</h2> 
<br>
// Initializes the local directory as a repository
1) git init 
<br><br>
// Start tracking files <br>
2) git add "NameOfFile.ext" 
<br><br>
// Save point (commit) <br>
3) git commit -m "Adding README with some commands" 
<br><br>
// Link the repositories together <br>
4) git remote add origin url-to-github-here
<br><br>
// Uploads every change to github <br>
5) git push -u origin master git push -u origin main
<br><br>
// Show the current file tracking status git status
6) git status
<br><br>
// add all the elements on the folder
7) git add .
<br><br>
rm -rf .git (Removes all configuration)