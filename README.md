[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287282&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

  Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


    Comprehensive Developer Environment Setup Document
    This document outlines the steps taken to set up a developer environment on Windows 11, including the installation of necessary software and configurations. It also includes customizations and troubleshooting steps encountered during the process.

      1. Install Windows 11
Steps:
Visited the Windows 11 Download Page.
Clicked "Download Now" to get the Installation Assistant.
Ran the Installation Assistant and followed the on-screen instructions to upgrade to Windows 11.
Troubleshooting:
Issue: Compatibility error during installation.
Resolution: Ensured all Windows updates were installed and checked hardware requirements.

      2. Install Visual Studio Code
Steps:
Visited the Visual Studio Code Download Page.
Selected Windows as the operating system and downloaded the installer.
Ran the installer and followed the prompts to complete the installation.
Customizations:
Enabled settings sync to keep settings, extensions, and themes consistent across devices.
Troubleshooting:
Issue: Extensions not loading.
Resolution: Restarted Visual Studio Code and reinstalled the extensions.

        3. Set Up Version Control System
   Install Git
Visited the Git Download Page.
Downloaded the Git installer for Windows.
Ran the installer and followed the prompts, keeping the default settings.
   Configure Git
Opened Git Bash.
Set the username and email:
Create a GitHub Account
Visited GitHub.
Signed up for a new account.
Initialize a Git Repository
Created a new folder for the project.
Opened Git Bash in that folder.
Created a README file and made the first commit:
Troubleshooting:
Issue: SSH key not recognized by GitHub.
Resolution: Generated a new SSH key and added it to the GitHub account.
      4. Install Python
Steps:
Visited the Python Download Page.
Downloaded the latest version of Python.
Ran the installer, ensuring to check the box to add Python to PATH.
Completed the installation.
Troubleshooting:
Issue: Python not recognized in the command line.
Resolution: Verified the PATH variable included Python and restarted the command line.
       5. Install Package Managers
Verify pip Installation
pip is automatically installed with Python. Verified the installation by running:
pip --version
Troubleshooting:
Issue: pip not found.
Resolution: Reinstalled Python, ensuring the option to install pip was checked.
      6. Install MySQL
Steps:
Visited the MySQL Download Page.
Downloaded the MySQL Installer.
Ran the installer and followed the prompts to install MySQL.
Troubleshooting:
Issue: MySQL service not starting.
Resolution: Checked for port conflicts and ensured the MySQL service was set to start automatically.
     7. Optional: Install Docker
Steps:
Visited the Docker Desktop Download Page.
Downloaded Docker Desktop for Windows.
Ran the installer and followed the prompts to complete the installation.
Troubleshooting:
Issue: Docker not running due to WSL 2 installation issue.
Resolution: Installed the WSL 2 Linux kernel update package for Windows.
       8. Explore Extensions and Plugins for Visual Studio Code
Steps:
Opened Visual Studio Code.
Went to the Extensions view by clicking the Extensions icon in the Activity Bar on the side.
Searched for and installed useful extensions:
Python (for Python development)
GitLens (for Git integration)
Prettier (for code formatting)
ESLint (for JavaScript linting)
Customizations:
Configured settings for each extension to match project requirements.

   During the setup process, several challenges were encountered:
Issue: Compatibility error during Windows 11 installation.
Resolution: Ensured all Windows updates were installed and verified hardware requirements.
Issue: Extensions not loading in Visual Studio Code.
Resolution: Restarted Visual Studio Code and reinstalled the extensions.
Issue: SSH key not recognized by GitHub.
Resolution: Generated a new SSH key and added it to the GitHub account.
Issue: Python not recognized in the command line.
Resolution: Verified the PATH variable included Python and restarted the command line.
Issue: pip not found.
Resolution: Reinstalled Python, ensuring the option to install pip was checked.
Issue: MySQL service not starting.
Resolution: Checked for port conflicts and ensured the MySQL service was set to start automatically.
Issue: Docker not running due to WSL 2 installation issue.
Resolution: Installed the WSL 2 Linux kernel update package for Windows.




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
