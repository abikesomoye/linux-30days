# Day 20 - Bash Script Anatomy

## Objective

What was the goal for today?

Introduction to Bash Scripting

---

## What I Learned

- Shebang (#!):

The first line in a bash script typically starts with #!/bin/bash
Specifies which shell should interpret the script

- Comments:

Lines starting with # are comments and are ignored during execution
Useful for documenting the script

- Commands:

Shell commands like ls, cd, echo, pwd are executed sequentially

- Variables:

Used to store values or user input for reuse in commands
Example: MYDIR="/home/user/projects"

- Control Structures:

Conditional statements: if...then...else, case
Loops: for, while, until



---

## What I Built / Practiced

- #!/bin/bash
- #This script displays the current directory and lists all files

- echo "Current Directory:"
pwd
- echo "Files in Directory:"
ls -l
- To run it use bash script_name.sh but if #!/bin/bash in the first line simply run it using./script_name.sh

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Bash stands for Bourne Again Shell and its the default for mac and Unix systems.
- By default, scripts do not have execution permissions. To make it executable chmod + x file

---

## Resources

- geeksforgeeks

---

## Output

(Include links, screenshots, code snippets, or results)
