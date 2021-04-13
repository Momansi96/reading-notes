# Read02

[Return to home page](https://momansi96.github.io/reading-notes/). 

### Git 

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

#### Files in Git can reside in three main states: committed, modified, and staged.

- Committed
Data is securely stored in a local database
- Modified
The file has been changed but not committed to the database
- Staged
Flagged a file’s changed version to be committed in the next snapshot

### Setting up a Git Repository

- Importing : 
1- Switch to the target project’s directory. 
2- Use the git init command. 
3- To start tracking these repository files, perform an initial commit. 

- Cloning : 
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL. 

### Local Repository Structure
The local Git repository has three components:

1- Working Directory: The actual files reside here.
2- Index: The area used for staging. 
3- Head: Points to the most recent commit. 

![imamge](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png). 

#### The Life Cycle of File Status: 

1- After you edit a file, Git flags it as modified because of changes made after the previous commit.
2- You stage the modified file.
3- Then, you commit staged changes.

### Some of the commandes to use : 

1- Check File Status: you can do that by using the command (git status). 

2- Tracking and Staging a Newfile : 
  - single file: you can do that by using the command (git add file name).
  - all files:  you can do that by using the command (git add *).

3- Committing a file: you can do that by using the command (git commit -m "why are you making a change"). 

4- Pushing changes: you can do that by using the command (git push origin main). 

Those are some of the  features existing in **Git**. 

And for any more help head to the [link](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#6_2). 



