## Instructions:
# HOW TO PUSH/UPDATE THROUGH GITHUB
1. git init - to initialize the path of the files in the folder 
2. git add . / git add <file_name> - adds the file in the folder through github
3. git branch -M main - connects vscode to github
4. git config --global user.name "username" & git config --global user.email "email" - verifies your github through the vscode.
5. git remote add origin https://github.com/username/repository_title.git - connects your github through vscode
6. git commit -m "your message" - commits the files inside the folder with a message.
7. git push -u origin main - finally pushes the files inside the redirectory to github.

# HOW TO FIX THE "GIT" PROBLEM
1. Find the directory pathing folder of Git itself
2. Right Click any version of the Git Application and click "Open File Location"
3. Copy the path of C:\Program Files\Git\cmd
4. Search and Open "Edit the system environment variables"
5. When opened, find and click "Environment Variables"
6. Look for "Path" in the System Variables and then click on it
7. Add a new pathing for the Git CMD to work, insert "C:\Program Files\Git\cmd" as the directory pathing
8. Click "Ok" and then save your changes. Everything should work fine if you input "git --version" in your terminal inside VSCode.

# HOW TO LOG OFF SOMEONE'S GITHUB IF IT DOESNT WORK (git push)
1. Press Windows, search and open "Manage Windows Credentials"
2. Look for "Windows Credentials"
3. Find "git:https://github.com"
4. Remove the other user's account
5. And everything should be working fine if you try doing "git push -u origin main" again.

Thank you.