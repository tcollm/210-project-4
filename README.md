# Project4: Inter Process Communication Using FIFOs

In this project, you are going to extend the restricted shell, rsh, to incude a command to send messages to other users. The **sendmsg** command :

You can use the starter code rsh.c to complete the project. A Makefile is also provided for convenience.

**Useful tips:**




### Github Repo Setup and Gradescope Submission Instructions

The setup of the git repo is similar to the one for Project 2. Refer to those instructions for your github repo setup.

For Project 3, create a separate private repository specific for this project under your own user name. For example, I created a private repo named **csci210_project3** and my github username is tolgacan. A private repo can be created from the GitHub web site by going to your repositories after clicking on your profile picture (e.g., https://github.com/tolgacan?tab=repositories) and clicking on the "New" button in the top right corner. After that, you can enter a command sequence similar to the one below to clone the starter repo and copy it to your private repo to work with. The **project3** repo under the organization **CSCI210Mines** is the public repository that contains the starter code.

```
git clone git@github.com:CSCI210Mines/project3.git
cd project3
git remote remove origin
git remote add origin git@github.com:tolgacan/csci210_project3.git  # this is my private repo. replace it with your own private repo
git branch -M main
git push -u origin main
```

After these commands, you should have a copy of your starter code in your own repo and you can update the **rsh.c** with your solution code and execute the following git commands to push your updates to your own repo:

```
git add rsh.c
git commit -m "your commit message here"
git push -u origin main
```

You can also clone your repo and work on it and push the updates from different machines if you add the ssh public keys for these machines to your github profile.

**Submission on Gradescope:**

After you are logged in to your github account in a browser, if you follow the Gradescope assignment page for this project from Canvas and try to upload a submission, you will be able to select the Github submission options and select your private repository for this project to submit your solution on Gradescope.
