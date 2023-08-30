# Part 3: Git Manual Questions
### Sheridan Lucas

## Imagine you are working at a game studio, and they want you to help with installing Git.

### 1.	Write instructions on installing git on a windows system. Making sure to include

#### a.	What are the requirements to install Git on a system.
#### b.	If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.

### System requirements for installing Git: <br>
* Git for Windows requires Windows 7 Service Pack 1 or later
* At least 258.1MB of free disk space
### Instructions for installing Git: <br>
1. Click [this link](https://git-scm.com/download/win) to install Git.
1. Select the latest version of Git for your system and click download. 
1. Start the Git installer 
1. Accept the Licence Agreement by clicking Next >
1. Select an installation folder by pasting in [C:\Apps\Git] <br>
	Click Next >
1. Select the following components:
	* Additional icons
		* On the Desktop
	* Windows Explorer intergation
		* Git Bash Here
		* Git GUI Here
	* Git LFS (Large File Support)
	* Associate .git* configuration files with the defult text editor
	* Associate .sh files to be run with Bash <br>
	Click Next >
1. Select start menu folder - accept the suggested name and click Next >
1. Choose defult editor Nano and click Next >
1. Select defult branch name - choose "Let Git Decide" <br>
	Click Next >
1. Adjust PATH environment - Select "Use GIT from Git Bash only" <br>
	Click Next >
1. Select HTTPS transport - Select "Use the OpenSSL library" <br>
	Click Next >
1. Configure line ending conversions - Select "Checkout Windows-style, commit Unix-style line endings" <br>
	Click Next >
1. Select behaviour of Pull Command - Select "Default" <br>
	Click Next >
1. Select credential helper - Select the recommended choice <br>
	Click Next >
1. Configure extra options - leave options unchecked <br>
	Click Next >
1. Configure experimental options - leave options unchecked <br>
	Click Next >
1. Let the installation complete <br>
	Click Finish


<br>
If you have any issures installing Git on your system, please reach out to our IT team on 1800 000 000. 

### 2.	Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 

#### a.	List the most important principles/techniques for creating and working with repositories
* Always have the most current version of your project in the master repository
* Keep repositories easy to understand by commiting small changes frequently
* Using branchs for individual team participants

#### b.	List the most important principles/techniques for creating and working with branches
* Identify and use a branching strategy.
* Create a branch for each feature
* Delete your local and remote branches after merging
* Merge early and often
* Avoid merge commits 


### 3.	List the steps in a Git workflow that the team should follow when working on projects.
1. Clone repository.
1. git fetch and git rebase.
1. Create a new branch.
1. Add commits.
1. git fetch and git rebase (on the main branch)
1. Push the commits.
1. Create a Pull Request.
1. Discuss, review and merge pull request.
