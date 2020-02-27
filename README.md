# EthylAcetate
## Table of contents
* [General info](#general-info)
* [Working on this Repository](#working-on-this-repository)
	
## Working on this Repository
### Initial Setup and Updating
In order to initially add this repository to your computer, type the following into command prompt/terminal.  
```
$ cd /Users/Write Username Here
$ git clone https://github.com/Nachreld/EthylAcetate.git
```
cd (change directory) is just used to get to the location you would like the file to be in.  For information on setting up git and moving through directories using command prompt, see [this video](https://www.youtube.com/watch?v=MFtsLRphqDM&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=3&t=0s).<br><br>
Once the repository has been set up you must use 'cd' to navigate inside the git repository on your computer.  You can update to all changes made to the remote repository on github by typing:
```
$ git pull
```
### Saving Changes (Performing a Commit)
In order to save changes to your branch once you have reached a good checkpoint, you must perform a commit.  More in depth instructions can be viewed in [this video](https://www.youtube.com/watch?v=Fhgga2s_RmM&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=6). Begin by typing:
```
$ git status
```
The command prompt will then list files that have been changed since the last commit in red.<br><br>
Before performing the commit, these files must be added to the staging area.  They can be added one by one using:
```
$ git add "filename"
```
or altogether by using:
```
$ git add .
```
<br>After adding the files, typing 'git status' again should show the files in green, meaning they have been added to the staging area.  You can the do the commit by typing:
```
$ git commit -m "Notes about changes here"
```
Make sure you enter detailed notes about what changes were made.
<br>After doing the commit, you can sync with the remote directory by typing:
```
$ git push
```