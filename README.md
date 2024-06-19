[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283911&assignment_repo_type=AssignmentRepo)
# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

1. Steps ivolved in downloading Windows 11 on my PC

   ANSWER:
   a. Some months ago before I joined the Power Learn Project Program, I updated my PC Windows version from Windows 10 to 11, and all I had to do was check for new updates via the windows update section from my PC settings, and I downloaded the latest update.


2. Install a Text Editor or Integrated Development Environment (IDE):

ANSWER:
a) I had Note pad ++ already installed on my computer
b) I downloaded Visual Studio Code Setup 64-1.90.0 version on my local machine via the https://code.visualstudio.com/Download, then installed it by following the installation prompts.
c. it was dark theme already when I launched VS code on my local machine thr first time, and since I liked it I did not have to change it.
d. I clicked Ctrl+Shift+x to search for extensions on the VS code, where I downloaded the python extension, code runner extension, and the gitbash extension

3. Set Up Version Control System:

   ANSWER:
   The following steps were taken to install and configure Git on my local machine:
   1) I downloaded Git-2.45.2-64-bit version on my local machine via gitforwindows.org, since my local machine is 64 bits, and installed on my local machine by following the installation prompts and selecting the default options.
   2) I set up an account on Github using my email, username and password via https://github.com
   3) I opened Git Bash (which automatically reflected on my desktop page after I installed Git) and started a command prompt and did the following:
   - I confirmed my Git version by inputing the command: git --version, after which my Git version showed
   - Then I had to configure my Git by running the commands: 
     git config --global user.name "Omolola.Eniola"
     git config --global user.email "eniolalola12@gmail.com"
   4) To create a directory still on gitbash, 
a.I ran the command: mkdir demo
b.Then ran the command: cd demo
c. Then I created a new public repository via my Git account, named 'demo' with a description- this is a demo project for training purposes
d. I ran the command: git innit to initialize an empty repository in my local disk C on my local machine
e. I created a text document in the demo folder and named it 'Test'
f. I ran the command: git status to check the most recent changes made which reflected, however, with no commit and my text.tx file untracked.
g. To ensure the test.txt in the repository is tracked, I ran the command: git add test.txt
h. To confirm the changes made, I ran the command: git status, and all changes reflected (the test.txt file is now tracked)
i. Also, I confirmed the title of my branch by running the comand: git branch ,and it showed that my branch name is 'master'
j. I ran the command: git commit -m "This is my first commit" to commit that message into the test.txt in the demo file
k. To link the remote repository on my local machine to my github, I copied a command: git remote add origin https://github.com/Omolola.Eniola/demo.git
l. To push the linked repository to reflect on my Github, I ran the command: git push -u origin master, a response showing something about emerging object confirmed that it has been pushed
m. Then I refreshed my githb repsitory page, and all changes reflected. 
n. Also, I created and added a new .md file titled 'author.md' with a message containing my name and email address, and clicked on commit changes to link my local repository to my remote repository.

Link to the my final repository on my github account obtained using the steps explained above: https://github.com/Omolola-Eniola/Demo



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

ANSWER:
The following steps were taken to dowload python:
   - I download python-3.12.4-amd64 version from http://www.python.org
   - I installed python and selected the path to customize installation to be saved on my local disk C, and followed all installation prompts to complete the installation. 
5. The python launcher automatically was ticked in the checkbox and was installed too along side python.
   -I had to run python on the command prompt via terminal by inputting the command: python --version, and the python version on my local mahine showed to be 3.12.4

5. Configure a Database (MySQL):

ANSWER:
The following steps were taken to install and configure MySQL 
- I downloaded MySQL 8.0.37 version from https://dev.mysql.com/downloads/installer/
- I also downloaded the MySQL Installer.
- I selected 'server only' for setup type, and 'development computer' for configuration type, followed other installation prompts and run the downloaded installer  to complete installation.
- then I ran the command: C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console to start the MySQL Server on Windows for the first time on my local machine

7. Challenges encountered during set up:

ANSWER:
The only challenge I encountered was durijg the download of python on my local machine. For some reasons that I do not know, the initial python.exe that I downloaded, there was no option to click on 'path', but I had to delete that particular file, and installed another version whuch eventuallyb worked on my local machine. I confirmed that it is working on my local machine by running the command 'python --version' on command prompt


