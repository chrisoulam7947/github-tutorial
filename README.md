# GitHub Tutorial
Q
_by Chrisoula Manguravdos_

---
## Git vs. GitHub
**You will learn how to:**

1. Create and use a repository

2. The initial setup


3. Open and merge a pull request

4. Repository Setup

5. Workflow and Commands

6. Error handling 

7. How to roll back changes

**What is Git?**

Is version control: It takes snapshots of your code 

Snapshot- keeps older version of your code

Doesn’t require github

Runs in the command line

Basic workflow

You have a directory (folder) of files

Once we initialize git (for version control), we call it a repository (repo for short)

Edit files (save them on the way) 

Add files (to the stage) 

Commit them 

**What is Github?**

* GitHub is a coding platform for version control and collaboration.

* It lets you and others work together on projects.
* You’ll learn how to:






---
## Initial Setup



---
## Repository Setup
A **repository** is usually used to organize a single project.

Repositories can contain folders and files, images, anything your project needs. 

**How to create a new repository:**

In the upper right corner, next to your avatar, click and then select _New repository_.

Name your repository according to what you are doing. 

If you want you can write a short description saying what your repository is about.

Leave everything else as it is and click _Create repository_

**Congratulations!**, You made a repository




---
##  Workflow and Commands

**pwd**

Prints working directories 

**ls**

Lists all the directories you have 

**cd**

Takes you to that directory

**mkdir**

Adds directory

**rmdir**

Removes directory

**touch**

It makes a file to the directory

**rm**

Removes files

**rm -rf**

Removes directory even if it includes anything inside

**mv (to rename)**

To rename your file 

**mv (to move)**

Moves and renames files

**c9 file**

takes you to the file you want that is present in the directory

**git init**

Initializes git in our directory for version control. Only do this once in the beginning 

**rm -rf .git**

If you do git in the wrong folder. This will correct it 

**git add file**

Add file to stage so that it can be committed.

**git add .**

Adds the current./entire directory: all files that have changed. (going to be green) Will not add to stage any deleted or renamed files 

**git add --all**

Include all changes, including deleted files.Will add any deleted or renamed files 

**git commit -m "message"**

Take a ‘snapshot’ of the files on the stage. The snapshot should be present-tense and describe what was modified in this snapshot (create HTML template’)

**git remote add origin URL**

git: a git command

remote: we are setting up a connection between our current repository and an external one (that lives on github)

add: we are adding the remote repo (as opposed to editing or removing an existing one)

origin: this is our “nickname” for the remote repo.  “origin” is standard.  In the future, you might need multiple remotes.

URL: the location of the remote repo. 

**git push -u origin master:**
Push: we are sending our commits from our local repo to our remote repo
-u: means “upstream” This tells git remember which remote repo and branch to push our changes to when type git push in the future


**git push**
We are sending our commits from our local repo to our remote repo
**git diff**
Show difference between current code and the previous commit
**git log**
see your past commits 
q (while in git log)


git checkout -- file


git reset HEAD file


git remote -v


**Git status**

Optional command to see which files have been edited since the last commit. (will be red). 

Command to see which files are staged for the commit (they will be green). (**remember: press “up arrow” twice)

**Git pull**

Bring any changes from the remote to local repo



---
## Error Handling 
If you ever happen to do git init in ~/workspace, **DON'T PANIC**. All you have to do is rm -rf .git



---
## Rolling Back Changes
Have  you ever wanted to undo something you did but didn't know how?.

**Here is how** 

The way to undo an edit is by using git checkout -- filename

The way to undo an add is by using git reset HEAD filename

The way to undo a commit is by using git reset --soft HEAD~1

The way to undo commits and adds is by using git reset HEAD~1

The way to undo commits and eddits is by using git reset --hard HEAD~1
