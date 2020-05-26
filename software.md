---
layout: page
title: Software
---

Our classes are designed to help you learn relevant concepts and skills in ways that you can apply directly to your own research.
You should be prepared to participate in each class by following along with the course material and completing challenge exercises provided by the instructor.

All software is open source and free unless otherwise noted.
Software installations for most classes should take less than 10 minutes.
If you already have the required software installed,
you may wish to check and ensure you have upgraded to the most current versions.
If you have any questions or problems regarding software installation,
please contact your instructor.

- [In-person courses](#in-person-courses)
- [Online courses](#online-courses)
- [Course-specific instructions](#course-specific-software-requirements)


### In-person courses

Please bring a laptop to each class with all required software for your course pre-installed.  
If you do not have a laptop assigned to you by Fred Hutch,
you are welcome to bring your personal laptop for use in class.
If neither of these options are available,
please contact your instructor to arrange use of one of computers available in the Coop Lab for classroom use.


### Online courses

Prior to the first class meeting,
please ensure you have all required software for your course installed.
We will not be using any resources that require connecting to the Fred Hutch network
(e.g., no VPN required, unless you are using a work-provided laptop that requires remote login for all activities).
You are welcome to use a personal computer for this class.

Class meetings will be held via MS Teams.
Connection information to join the meeting will be included in an Outlook calendar invitation,
and also available on the course webpage included in the welcome email.
Please confirm your internet connection is strong and stable for each class session.
If you haven't used MS Teams before,
here are some helpful hints:
- You are not required to share your video during class, though you may find it useful to ask questions via audio. We ask that you keep yourself muted unless you are asking a question to minimize background noise, and use headphones if your physical location is especially noisy.
- There is both a web version and stand-alone application for meetings in Teams. If you’re having trouble connecting on the web version, try switching browsers (we’ve had success with Safari and Chrome, but Firefox was problematic). You may need to update your security/privacy preferences to allow the software access to your microphone (we've encountered this issue on some Macs). If you can't get audio to work through Teams, you can also use a phone to call in (see connection details for the phone number and conference ID).
- If you are having trouble with materials in class, your instructor may ask for you to share your screen. The screen share button can be found next to the audio and video buttons at the bottom of the Teams screen. You have the option to share either your entire screen or only a specific window (e.g., the software in which you are executing code); the latter is generally sufficient.


### Course specific software requirements

- **Data for Data Science**: [spreadsheet program](#spreadsheet-program) (like Microsoft Excel) and a [text editor](#text-editor) (like Atom), [course description](http://www.fredhutch.io/resources/#data-for-data-science)
- **Concepts in Machine Learning**: no software required, [course description](http://www.fredhutch.io/resources/#concepts-in-machine-learning)
- **Introduction to Git and GitHub**: [GitHub Desktop App and command line tools](#git-and-github), [course descriptions](http://www.fredhutch.io/resources/#introduction-to-git-and-github)
- **Introduction to R**: [R and RStudio](#r-and-rstudio) and [tidyverse](#tidyverse), [course description](http://www.fredhutch.io/resources/#introduction-to-r)
- **Intermediate R: Machine Learning**: [R and RStudio](#r-and-rstudio), [course description](http://www.fredhutch.io/resources/#intermediate-r-machine-learning)
- **Introduction to Python**: [Jupyter notebooks, via Anaconda](#python-jupyter-notebooks) and [plotnine](#python-plotnine), [course description](http://www.fredhutch.io/resources/#introduction-to-python)
- **Intermediate Python: Machine Learning**: [Jupyter notebooks, via Anaconda](#python-jupyter-notebooks), [course description](http://www.fredhutch.io/resources/#intermediate-python-machine-learning)
- **Intermediate Python: Programming**: your choice of [interface](#python-other-interfaces), [course description](http://www.fredhutch.io/resources/#intermediate-python-programming)
- **Software Carpentry Bootcamp: Unix, Git, and Python**: you will receive an email prior to class with software installation instructions, [course description](http://www.fredhutch.io/resources/#software-carpentry-bootcamp-unix-git-and-python)


### Spreadsheet program

Spreadsheet programs (e.g., Microsoft Excel) are a useful way for us as humans to interact with data. The most common of these is Microsoft Excel. Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same.
If you are working on a computer owned by Fred Hutch,
Microsoft Office (including Excel) is available through the Self Service application.
If you are working on a personal computer that doesn't have a spreadsheet program, you can use a free, open source program called LibreOffice.

* Install LibreOffice by going to the [installation page](https://www.libreoffice.org/download/download/). The version for your operating system should automatically be selected. Click Download Version X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don’t need to make one. Your download should begin automatically.
* Once the installer is downloaded, double click on it and LibreOffice should install.


### Text editor

Text editors allow us to understand how computers may interact with our data. We recommend installing [Atom](https://atom.io) if you do not already have a preferred text editor (the link should auto-detect your operating system). Please note that the default text editors on most computers (Notepad on Windows and TextEdit on Mac) are not optimal for this course.


### Git and GitHub

Git is version control software, which helps you keep track of changes made to files.
GitHub is a repository for data and code tracked with Git, and is a mechanism for publishing
and collaborating on project development.


#### GitHub Desktop App

* If you do not already have one, please register for a [GitHub](https://github.com) account.
Please note that your name and email will be publicly visible through GitHub by default,
but more information on controlling privacy settings can be found
[here](https://help.github.com/articles/setting-your-commit-email-address-on-github/).
* The website for [GitHub Desktop](https://desktop.github.com) should auto-detect your operating system
and allow you to download and install the software. If you have difficulty installing the GitHub Desktop App
(which has been reported for some Hutch-owned PCs),
please install the command line tools for Windows as described below.
* We recommend installing [Atom](https://atom.io) if you do not already have a preferred text editor;
this website will also auto-detect your operating system.
* If you would like to participate in the optional
third class for command line git, please see the section below for more information.

#### Command line tools: Windows (only for optional third class)

If you would like to work with Git on the command line in the third week of class on a Windows laptop,
also install [Git for Windows](https://gitforwindows.org). Please note that this also installs Git GUI,
which we will not use (unless you have difficulty installing the GitHub Desktop App, as described above).


#### Command line tools: Mac (only for optional third week)

If you would like to work with Git on the command line in the third week of class on a Mac laptop,
you will need to ensure the command line git tools have been installed.

Please open a Terminal window and execute `git status`.
If you receive the following error:
```
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools),
missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
```
Execute the following line of code to install the command line tools: `xcode-select --install`.
This error has occurred for MacOSX Catalina.

The following error is what you should expect to see if you have successfully installed git:
```
fatal: not a git repository (or any of the parent directories): .git
```
If you receive a notification that git is not found,
you may need to install command line Git tools by clicking on "GitHub Desktop" in the top menu of the app,
then selecting "Install Command Line Tool."


### Python: Jupyter notebooks

We recommend installing Python using Anaconda to be able to access [Jupyter notebooks](http://jupyter.org). Anaconda comes with a number of other useful packages, including [pandas](http://pandas.pydata.org), [numpy](http://www.numpy.org), and [matplotlib](https://matplotlib.org).
Install Anaconda using the following instructions:
* Download the [Anaconda](https://www.anaconda.com/download/) installer for
Python 3.x for your particular operating system.
* Double-click the downloaded file and follow the prompts to install Anaconda (default options are acceptable).
* For assistance troubleshooting installation, please go [here](https://jupyter.readthedocs.io/en/latest/install.html).

To check if you've successfully installed Anaconda,
open the Anaconda Navigator application and click on the button to launch a Jupyter notebook.
You should see a file browser open in your default web browsing application.


### Python: plotnine

We will use [plotnine](https://plotnine.readthedocs.io/en/stable/) for data visualization. Following installation of Anaconda, install plotnine by opening the following command line software based
on your operating system:
* MacOSX: Terminal, locate by clicking on your Desktop, selecting "Go" in the menu at the top,
and clicking on "Utilities"
* Windows: Anaconda Prompt

For both MacOSX and Windows, copy and paste the following code onto the
command line (in the window of the program you just opened) and execute by hitting "Enter":

`conda install -c conda-forge plotnine`

If you are working on MacOSX and receive an error for the command above indicating "conda is not found",
but you have successfully installed Anaconda (see above),
you may need to activate `conda` for `zsh` (the new default shell as of MacOSX Catalina)
by executing the following command in Terminal:
```
/anaconda3/bin/conda init zsh
```
Please note that `/anaconda3/` represents the installation location for Anaconda on your computer.


### Python: other interfaces

Unless we specify use of [Jupyter notebooks](#python-jupyter-notebooks), you are welcome to use whatever interface is most comfortable for you for executing Python code. Some suggestions are as follows (please see the HackMD page for your course to see what your instructor will be using):
* [Atom](https://atom.io): a text editor, which requires you to also install [Hydrogen](https://atom.io/packages/hydrogen) as well as a separate version of Python (e.g., if you've already installed Anaconda)
* [Visual Studio Code](https://code.visualstudio.com): a streamlined code editor that is recommended by Scientific Computing at Fred Hutch (*preferred*)
* [Spyder](https://www.spyder-ide.org): a scientific IDE (integrated development environment) installed with Anaconda and available in the Anaconda Navigator


### R and RStudio

R and RStudio are separate downloads.
R is the "engine", while RStudio is an integrated desktop environment (IDE) that makes using R much more pleasant.
R must be installed before RStudio.
Follow the instructions below for your operating system to install them.
If you are working on a computer owned by Fred Hutch,
RStudio + R is available through the Self Service application.


#### Windows

* Download the installer for the latest version of R from [CRAN](http://cran.r-project.org/bin/windows/base/release.htm).
  The file will begin downloading automatically.
* Double-click the downloaded `.exe` file and follow the prompts to install.
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download).
* Under _Installers_, click the link for the _Windows Vista/7/8/10_ installer to download it.
* Double-click the downloaded `.exe` file and follow the prompts to install (default options are acceptable).
* Once both are installed, launch RStudio and make sure there are no error messages.


#### macOS

* Download the installer for the latest version of R compatible with your version of macOS from [CRAN](https://cran.r-project.org/bin/macosx/).
  If you are not using a recent version of macOS you may have to scroll down to _Binaries for legacy OS X systems_ and find the one appropriate for your version of macOS.
  To check what version of macOS you are using, click the apple icon in the upper left corner of your screen and go to _About This Mac_.
  Please note the instructions on that page for downloading and installing [XQuartz](https://www.xquartz.org/) if necessary.
* Double-click the downloaded `.pkg` file and follow the prompts to install (default options are acceptable).
* Go the the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download).
* Under _Installers_, click the link for the your OSX version's installer to download it.
* Double-click the downloaded `.dmg` file, then open the RStudio folder that appears on your desktop. Drag the RStudio icon into the Applications folder.
* Once everything is installed, launch RStudio and make sure there are no error messages.


### tidyverse

- Open Rstudio. 
- Click the Packages tab in the lower right panel. 
- Click the Install button (upper left corner of the panel). In the empty space for Packages, type `tidyverse`. The other defaults (Install from CRAN and the Install to Library path) should be ok. Make sure the box next to "Install dependencies" is checked, and click Install.
- If your installation is successful, you should see tidyverse appear in the list below. 
