# GR13_Speech_recognition

This readme is meant to provide the user with important informations regarding how to properly run the code. The user can choose what file to run based on his/her OS and should  also have installed the listed Python libraries. We also provide some specifications about SVN.

## 2 code versions:
* Windows
* MacOS, Linux

the difference lies in one line of code in the filename splitting process. Windows uses backslashes ( \ ) for paths to directories, while MacOS (and Linux) use the forward slash ( / ). This difference plays a major role in the filename splitting process in our project.

## Python libraries used:
* Librosa
* Scikit Learn
* Numpy
* Pandas
* Matplotlib
* IPython
* OS

## SVN 
In our code we implemented the data files retrieval via SVN. SVN stands for Subversion, which is a version control software. We used one of the basic SVN commands, "checkout", which automatically creates a working copy of the files contained in the GitHub repository in a local repo on the user terminal.  

If the user gets an error while running the cell related to the !svn checkout command, we suggest to:
1) make sure the path to svn has been added in the section "System Variables",
2) svn.exe should be present in System32 directory.

This fixed the problem on Windows.
