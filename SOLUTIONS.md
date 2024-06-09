1. SETUP VERSION CONTROL SYSTEM WITH GIT AND GITHUB
2. Step 1: Install Git on Your Local Machine
Download Git:

Go to the official Git website: Git Downloads.
Click on the "Windows" button to download the installer for Windows.
Run the Installer:

Locate the downloaded installer file (Git-{version}-64-bit.exe) in your Downloads folder and double-click it to run the installer.
Follow the installation prompts, leaving most settings at their default values.
Ensure that the option "Git from the command line and also from 3rd-party software" is selected during the installation process.
Complete Installation:

Click "Next" through the remaining prompts and then "Install."
Once the installation is complete, click "Finish."
Step 2: Configure Git
Open Git Bash:

Open Git Bash by searching for it in the Start menu or selecting it from the list of installed programs.
Set Your Username and Email:

Configure your Git username by running the following command in Git Bash (replace "Your Name" with your actual name):
bash
Copy code
git config --global user.name "Your Name"
Configure your Git email by running the following command (replace "your.email@example.com" with your actual email):
bash
Copy code
git config --global user.email "your.email@example.com"
Verify Configuration:

To check if your configuration was successful, run:
bash
Copy code
git config --list
Step 3: Create a GitHub Account
Sign Up for GitHub:

Go to the GitHub website.
Click "Sign up" in the top right corner.
Follow the prompts to create a new account, including entering your email, creating a password, and choosing a username.
Verify Email:

Check your email for a verification message from GitHub.
Click the verification link in the email to verify your account.
Step 4: Initialize a Git Repository for Your Project
Create a New Project Directory:

Open File Explorer, navigate to the location where you want to create your project, and create a new folder (e.g., "MyProject").
Alternatively, you can create the directory using Git Bash:
bash
Copy code
mkdir MyProject
cd MyProject
Initialize Git Repository:

Open Git Bash and navigate to your project directory:
bash
Copy code
cd path/to/MyProject
Initialize a new Git repository in this directory:
bash
Copy code
git init
Create a New File:

Create a new file in your project directory (e.g., README.md). You can do this using Git Bash:
bash
Copy code
echo "# MyProject" > README.md
Add the File to the Repository:

Add the file to the staging area:
bash
Copy code
git add README.md
Make Your First Commit:

Commit the file to the repository with a commit message:
bash
Copy code
git commit -m "Initial commit"
Step 5: Push Your Project to GitHub
Create a New Repository on GitHub:

Go to GitHub and log in to your account.
Click the "+" icon in the top right corner and select "New repository."
Enter a name for your repository (e.g., "MyProject"), add an optional description, and choose whether it should be public or private.
Click "Create repository."
Connect Your Local Repository to GitHub:

In the "Quick setup" section of your new GitHub repository, you will see a URL (e.g., https://github.com/username/MyProject.git).
Go back to Git Bash and set the remote URL for your local repository:
bash
Copy code
git remote add origin https://github.com/username/MyProject.git
Push Your Code to GitHub:

Push your local commits to the GitHub repository:
bash
Copy code
git push -u origin master
If prompted, enter your GitHub username and password.


2.
