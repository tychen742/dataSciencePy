---
layout: page
title: Computer Setup
---

***We will use Python and introduce Git and SQL. You are encouraged to set up your computer during the first week so you will be ready when we bring them up in class.***

### Python

Download and install [Python](https://www.python.org/downloads/){:target="_blank"} (choose one minor version[^1] behind the current version; e.g., if the current version is 3.13, download 3.12 instead). 

### venv and pip

A Python virtual environment keeps specific Python version and required software dependencies of a project separate from the system-installed Python and packages. Inside your project folder, create a virtual environment by issuing `python -m venv .venv` (`.venv` is a convention but your can use any pathname) in the command line. To activate the venv, issue `source .venv/bin/activate` and your will see `(.venv)` in the front of the shell prompt denoting the venv activated. 

With `venv` activated, use `pip`, the package managemnet software for Python, to install packages and the packages will be installed in `.venv/lib/python<i>VERSION</i>/site-packages`. 

### VS Code
Download and install the most recent stable build of [Visual Studio Code](https://code.visualstudio.com/){:target="_blank"} (VSCode/VS Code). Learn how to set up VSCode by watchign a video such as [Setup Visual Studio Code](https://code.visualstudio.com/learn/get-started/basics). 

### Jupyter Notebook


### GitHub

1. Create an account on GitHub (https://github.com).
2. Email your username to your instructor.
3. Once your instructor adds you to the course GitHub organization, you will
   receive an email asking you to accept the invitation. Click on the link to accept.
4. Check if this worked
    1. Go to [https://github.com](https://github.com).
    2. Sign in if necessary.
    3. In the upper left corner click on the drop down with your name.
    4. Confirm that the name of the course GitHub organization is present.

### Git

#### Windows

1.  Install Git for Windows
    [installer](https://gitforwindows.org/).
2.  Run the installer and follow the steps bellow:
    1. Click on "Next".
    2. Click on "Next".
    3. Keep "Use Git from the Windows Command Prompt" selected and click on
       "Next". If you forgot to do the integration, with R will not work
       properly. If this happens, rerun the installer and select the appropriate
       option.
    4. Click on "Next".
    5. Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
    6. Keep "Use Windows' default console window" selected and click on "Next".
    7. Click on "Install".
    8. Click on "Finish".
3. Check if the installation is working:
    1. Open RStudio
    2. File -> New Project -> Version Control -> Git
    3. If you reach a page called `Clone Git Repository` with some fields to fill out everything is working

#### macOS 
*There are two ways to install git on your macOS. Pick one.*
1. Install through macOS Terminal:
    1. Open up the Terminal (command+space), type in "git" and press enter.
    2. This should cause a pop-up window to appear. It will have several options;
   click on "Install" (not "Get Xcode").
    3. Click "Agree".
    4. When the install is finished, click "Done".
    5. To make sure this works, type in "git" in the Terminal and press enter. Some
   information will come up, including a list of common commands. If this
   doesn't work, see additional instructions below.
2. Instal through the [git website](https://git-scm.com/) by downloading the lastest release. 

#### Linux

Git is probably already installed. If it is not already available install it via
your distro's package manager. For Debian/Ubuntu run `sudo apt install git`
and for Fedora run `sudo yum install git`.

### SQL

Download and install [DB Browser for SQLite](http://sqlitebrowser.org/)

[^1]: Semenatic versioning suggests a version number in the format of MAJOR.MINOR.PATCH and increment in specific condition. See <a href="https://semver.org/" target="_blank">