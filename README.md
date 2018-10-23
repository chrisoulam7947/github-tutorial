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
