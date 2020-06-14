- [Return to Home Page](/README.md)

# Class 03 Revisions and the Cloud

## Lab 03 Cloning a Repsository
In this lab, I 'cloned down' my learning journal 'repo' to Google Drive, so I can do all future work in VS Code. Here's how:

1. Open the GitHub repository, click the green "Clone or download" button and click the copy icon.
2. Open the terminal application on my computer. Type `cd ~/your/file/path` to point to a directory made specifically for this class.
3. Type `git clone https://github.com/mlhaus/learning-journal.git` to make a copy of this repository.
4. Type `cd learning-journal` to move into my repo directory.
5. Type `code .` to open the files in VS Code.
6. Use VS Code to organize and edit files. 
7. After every meaningful change, perform the following commands.
   - `git status` to see the changes made to my repository.
   - `git add .` to add all changes to a stage.
   - `git commit -m 'Short message'` to explain the changes.
   - `git push origin master` to send the changes to GitHub.
8. Refresh the GitHub repository and see the changes.
