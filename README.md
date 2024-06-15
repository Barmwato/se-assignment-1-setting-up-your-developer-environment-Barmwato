[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248626&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   1. First check for system compatibility
   2. Visit the Windows 11 product download page
   3. Navigate to the Create Windows 11 installation media link, and click Download Now.
   4. Once the tool downloads, double-click on the file in your download and run it. You may be asked for permission to run the program, so go ahead and approve it.
   5. Now that you have the Media Creation Tool running, follow the directions to download the ISO file.
   6. Make sure you select USB Flash Drive when prompted.
   7. Once the download is complete, eject your usb safely.
   8. Plug the USB drive into the computer and restart the computer.hold the F8 key or any other depending on your computer
   9. Choose the boot order and select the USB drive option as first.
   10. Press any key to continue booting from your specified location.
   11. After it is done,choose your account preference, time zone, Language
   12. Click on install now,wait for the process to finish up and you are good to go.




2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   1. Download the installer fro the official site
   2. Click the "Download" button.![alt text](<vscode site.JPG>) choose according to your system.
   3. Double-click the downloaded installer (.exe file).
   4. Follow the on-screen instructions, Choose a suitable installation location (default is usually fine).
   5. Check the option "Add VS Code to PATH"
   6. Click "Install" to begin the installation.
   7. After it is done,lauch it to be sure it has installed.

Once the installation is complete, you can choose to launch VS Code directly from the installer.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   1. Visit the official Git website: https://www.git-scm.com/downloads
   2. Under "Downloads", download the installer appropriate for your operating system
   3. Once it is done downloading, double-click the downloaded file to extract and launch the installer.
   4. Leave the defaults as you click next untill the installation is finished.
   5. Launch Git Bash, by opening the Windows Start menu, type git bash, and press Enter.
   6. Check the git version to verify it was installed ![alt text](<git version.JPG>)
   6. Configure the identity for creating commits to git hub account. Make sure the details are the ones to be used for creating github account.SHOULD be the same.
      1. git config --global user.name "[username]"
      2. git config --global user.email "[email]"

   Creating github account
   1. Search for github.com in your browser
   2. Sign up- Enter your email and password then click continue ![alt text](<setting up github-1.JPG>)
   3. Create your first repo in github --click on profilr--your repositories--new and name it exmaple PlpClass

   Creating first repo:
   1. Go to git bash, navigate to to where you want your first project saved cd D:/ example
   2. Create a Folder for the project example mkdir PlpClass then create a new text file example test.txt
   3. Navigate to the folder cd PlpClass, ls to if the file is there
   
   Connecting to github
   1. while in the project folder in git bash type git init then press enter
   2. add the text file in the folder by typing git add test.txt
   3. Commit it with a message with the command git commit -m "This is the first commit"
   4. Go to github copy the repo link
   5. come back to your git bash and type in git remote add origin <repolink> then enter
   6. Push the local repo to github by typing in command git push -u origin <branch> then enter.
   7. Finally go to git hub refresh the repo to confirm if it is successful.![alt text](<test pushed repo.JPG>)



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   1. Visit the official Python website
   2. Under "Downloads", select the latest stable version of Python
   ![alt text](<python download page.JPG>)

   3. Choose the appropriate installer for your operating system then download.
   4. Navigate to downloads folder and double click on the installer.
   5. Check on the chebox "Add Python 3.x to PATH" then click on install now.
   6. Once it finishes installing, search for environment variables to check whether the path was added.
   ![alt text](<add path in environment variables-1.JPG>)
   ![alt text](<envt variables.JPG>)
   7. Verify if python was installed by running the command python --version  ![alt text](<verifying python was installed.JPG>)



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   1. pip normally comes bundled with the official Python installer. to confirm you run pip --version command from the command prompt.
   ![alt text](<confirming whether pip is installed.JPG>)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   1. Visit the official MySQL downloads website
   2. Select the appropriate version based on your system and operating system version.
   3. Click the download link for the installer you want.

Installing MySQL:
   1. Run the downloaded installer (.msi file).
   2. Follow the on-screen instructions to install.Like choosing the instalation type(e.g., Server only, Client only, Full)
   3. Choosing a destination folder.
   4. Configure the root password and port number
   5. Apply configurations
   6 To see if it was successful go to my sql command line client then if prompts for password it is successful . Key in your root passowrd ,enter then view the details like version etc.![alt text](mysql.JPG)


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   1. Open VS Code.
   2. Click on the Extensions icon in the Activity Bar on the left side. alternatively use Ctrl+Shift+X
   3. Navigate to the Search bar to find extensions by keyword.
   4. Install your preffered extensions ![alt text](extensions.JPG)



   ###Done####



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
