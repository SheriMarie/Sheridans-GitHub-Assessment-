# Part 2: Questions
### Sheridan Lucas

one thing <br>
two thing
<p>three thing</p>

**bold**

- test
	- another
- last


```
fdfsdfsd;
sdf;
sdf
sd
fsd
fsd
code block example;
```





>this is something andrew has said



### 1.	List three major version control for software engineering. <br>
* Git (distributed)
* Mercurial (distributed) 
* Subversion (centralized)

### 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers. <br>
* Git's branching capabilities, they are easy to merge, have good data integrity, and provide an isolated environment for every change to code. 
* free and open-sourced
* Each developer gets a local repo with a history of commits that makes git faster than other cersion controls. 

### 3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge <br>

Branch:  A new and separate version of the main repository that can be merged. 
Pull: Downloads content from a remote repository, updating the local repository to match. 
Push: Uploads your local repository contecnt/changes to a remote repository 
Repository: Saves and tracks history of changes made to files in a Git project. Can contain various different versions. 
Working Copy: For Git, "working copy" is a directory full of files with a .git subdirectory. "working copy" are the files you actively work on.
Merge: Incorporates changes from one repository to another

### 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git. <br>
* OHS/WHS
* Use descriptive commit messages 
* Incorporate others changes frequently / Share your changes frequently 

### 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts. <br>
* meld
* opendiff
* kdiff3

### 6.	In a merged source code file, how does Git let you know there is a conflict? <br>
* git log command will produce a log with a list of commits that conflict between the merging branches.

### 7.	What are the steps you can take to resolve Git conflicts? <br>
1. After merging and Git identifies a conflict and will modify the file with conflicts
1. The most direct way to resolve a merge conflict is to edit the conflicted file and choose what to keep.

### 8.	What does git revert do, and how can you use it? <br>
* Git revert can undo prevoius changes in a commit without losing what you haven commited post that commit. 
### 9.	What does git reset do, and how can you use it? <br>
* Undo changes to conflicted files

### 10.	What is the difference between git revert and git reset? <br>
* Git revert is a forward moving undo that will create a new commit that inverses the changes specified while Git reset has 3 options (soft, mixed and hard) that vairy is how much the reset however will undo all local changes. Less controlled? 
### 11.	True or False: It is okay to commit broken code to the main branch. <br>
* False
### 12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits. <br>
* True
### 13.	Describe what is DevOps, how is it useful for game developers? <br>
DevOps is a technique that IT and Software Developers use to manage and complete projects to a higher standard faster by combining and automating the work of software development and IT ops teams. It aims to incorporate inputs from all stakeholders into the development process. Ultimately meeting software users demand for frequent new featured without inturpting performance and availability. 
### 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3) <br>
* Microservices - application is split into many small services
* Continuous Intergration/Continuous Delivery - incremental code changes are made frequently and reliably (tests code before upload) 
* Monitoring and Logging - monitor metrics and logs to see how application and performance impacts the experience of their product’s end user.
* Communication and Collaboration -  key cultural aspect of DevOps. Brings together the workflows and responsibilities of development and operations.
### 15.	What is CI/CD and how can it be used to automate the game development process? <br>
* Smaller chunks of new code are merged into the code base on a frequent basis. Code is automatically integrated, tested and prepared for deployment to the production environment, automating the game development process. 