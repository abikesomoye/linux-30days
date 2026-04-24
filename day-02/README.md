# Day 02 - Files

## Objective

What was the goal for today?

File Permissions and Ownership 

## What I Learned

- Types of users includes user,group others
- Types of permissions
- d refers to directory,- refers to file, l refers to link
- To view the file permission we use ls -l

---

## What I Built / Practiced

- r stands for read:view the contents of a file or list a directory
- w stand for write: Modify the contents a file, create or delete a directory
- x stands for execute: run the file as a program or access a directory
- a command like drwxrwxrwx means the d means its a directory the first set of permission rwx is for the owner, the second set is the group the owner is in and the last set is for all other users on the system.They all have read r, write w and execute privileges to the directory
- Another example is -rwxr-xr-- doyin devs 2560 extract.py means the owner is doyin who has read,write and execute permission to the file named extract.py. Doyin is part of the dev group who has only read and execute permission. Then all other users on the system can only read the file.They can't make changes.

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- permissions are also in numbers for example read is 4, write is 2 and execute is 1. when added up it give a combination 
- its a shorthand way of assigning permission eg chmod 754 extract.py the owner has rwx,group has r-x and others have r--

---

## Resources

- 04-linux-file-permissions-and-ownership/01-file-permissions-and-ownership.md by Najeeb Sulaiman 

---

## Output

(Include links, screenshots, code snippets, or results)
