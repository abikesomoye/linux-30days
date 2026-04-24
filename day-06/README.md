# Day 06 - Less Command

## Objective

What was the goal for today?

Learning Less command

---

## What I Learned

- The less command in Linux is used to view the contents of a file one page at a time without opening it in an editor, making it ideal for reading large files efficiently.
- It does not load the entire file into memory, making it faster for large files.
- It provides navigation shortcuts (e.g., Space for next page, b for previous page, q to quit).
- syntax is less [options] filename

---

## What I Built / Practiced

- Commonly used options are
- -F: Exits immediately if the entire file fits on the first screen. eg less -F /home/dev/first.txt
- -p pattern: Opens the file at the first occurrence of the specified pattern. eg dmesg | less -p "fail"
- -E: Automatically exits when the end of the file is reached eg less -E /home/dev/first.txt

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- 
- 

---

## Resources

- Datacamp Introduction to shell

---

## Output

(Include links, screenshots, code snippets, or results)
