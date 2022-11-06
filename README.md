##Author name and email <br />
git config --global user.name "Abhinandan" <br />
git config global user.email "abhinandanchou@gmail.com”<br />
#create a local folder directory and initialize a .git folder using git bash<br />
git init ==This will create a hidden folder git<br />
git status-check the status of the directory by using the Git command “status.”<br />
git add test.txt== staging new file in directory<br />
git rm --cached test.txt === unstaging the file in directory<br />
git commit -m  “initial commit”===adding a commit<br />
#How to create a .gitignore file on windows<br />
Open notepad or notepad++ or any text editor available.<br />
Type in the name of the file you want git to ignore e.g Private.txt.<br />
Save file as; filename : .gitignore, save as type: all text<br />
repeat the above git add git commit git status step<br />
#git log<br />
It also includes, for each commit<br />
• The name (unique, obtained by hash)<br />
• The author<br />
• The date<br />
• The description<br />
#pushing file to github account  remote directory<br />
first create a github account and then create a repository(to do)<br /><br />
run git bash on the local directory<br />
git remote add origin https://github.com/Abhi-nand/to-do.git=====add a link to the newly created repository<br />
git remote or git remote -v ====check if the remote has been added by executing  to get more information. <br />
“README.md ======for description of project in Markdown<br />
git push origin master=======The git push command to remote directory in github
