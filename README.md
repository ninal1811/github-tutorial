# GitHub Tutorial

_By Nina Li_

---
## Git vs. GitHub

Git is a high quality verison control system. 
GitHub is a hosting service where git is allowed to be performed. GitHub is desighed as a Git repository hosting service. GitHub allows you to code and share with others, giving others the ability to make edits.

---
## Initial Setup

The Initial Setup starts with an IDE(Integrated Development Environment). IDE is used for command lines, file trees, text editor, and preview.
#### Setup for IDE:
* You have to [create a GitHub account](https://www.github.com) or [login to GitHub account](https://www.github.com)
* Memorize this link **[ide.cs50.io](https://ide.cs50.io)** --> this is the link you will use to open up your IDE
* [Click here to setup for IDE](https://github.com/hstatsep/ide50)

---
## Repository Setup

* [Login to your GitHub account](https://www.github.com)
* [Login to your IDE](https://ide.cs50.io)
* Go to GitHub and manke a new repository
* Go into your IDE
To make a new repository, go to the top right hand corner and press the add sign **+** and press make repository. Create a name that you want to name the repository with and press create. **Keep in mind that your repository name and the directory name has to match.** After creating the repository, it will bring you to a page where there is three sections under Quick setup. For the Quick setup, make sure that the link is in **SSH FORM** and **NOT HTTP FORM**. Copy the codes from the "…or push an existing repository from the command line" section, which is the two lines that start with git

* Start by creating a directory by using **mkdir** and the name you want to name it
* Then go into the directory by using **cd** and directory name
* After being inside of the directory, initialize it by using **git init**
* Next you would make a README file by using **touch README.md**
* In order to open the file, you have to use **c9 README.md**
* Type what ever you want to add or needs to be add
* When done typing what is need, go back to the directory, **MAKE SURE THAT THE FILE IS SAVED, IF NOT, THEN USE COMMAND+S** and add the file by using **git add README.md**
* Next up is commiting it, use **git commit -m ""**, be sure to put a message inside the quote
* Now paste the code that you have copied from GitHub
* Finally, for any changes you make to the file, always remember to **git add README.md**, **git commit -m ""**, and **git push** to keeps your changes saved in your GitHub repository

---
## Workflow & Commands
