# Day 23 - Arguments

## Objective

What was the goal for today?
ARGV
--

## What I Learned

- ARGV is the array of all given to the program and each argument can be accessed through the $ notation
- $1 is the first, $2 is the second and so on
- $@ and $* returns all the arguments
- $# gives the number of arguments
- For example in a bash script
- #!/usr/bash
- echo $1
- echo $2
- echo $@
- echo 'There are " $# " arguments
- we run it using bash args.sh one two three four five, we get on the terminal
- one
- two
- one two three four five
- There are 5 arguments 

---

## What I Built / Practiced

- echo $1
- echo $2
- echo $@
- echo $#

- bash script.sh Bird Fish Rabbit

- the output was
- Bird
- Fish
- Bird Fish Rabbit
- 3
- 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Using these notations can greatly enhance the functionalities of tour scripts.
- 

---

## Resources

- Datacamp Introduction to Bash Scripting

---

## Output

(Include links, screenshots, code snippets, or results)
