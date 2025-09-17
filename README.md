Automation script using Selenium Web driver + java + TestNG
Steps to uploading all your project on github via commands . 
NO manual uploading is done
--------------------------------------------------------
Uploading a Selenium WebDriver project with Java and TestNG to GitHub generally involves using Git commands to connect your local project to a new or existing GitHub repository
Here is concize guide.

**Step 1: Initialize Git and stage your files**
1)  **git init**
2)  **git add .**


**Step 2: Commit your files**
Next, create your first commit. The commit message should be a brief description of the changes you're saving.

3) **git commit -m "Initial commit of Selenium TestNG project" **        //commit message can be any


**Step 3: Connect to GitHub and Push
**Now, create a new empty repository on GitHub. Do not initialize it with a README, .gitignore, or license file. Once created, copy the URL of the remote repository. 
Then, back in your terminal, add the remote repository as the "origin" for your local project and push your committed code to it.

4)  **git remote add origin [your_github_repo_url]**
5)  **git push -u origin main**
The -u origin main command sets the upstream branch, so in the future, you can simply use git push to upload changes.



