# Day 24 - Quotation Marks

## Objective

What was the goal for today?
Different Quotation Marks
---

## What I Learned

- Single quotes eg 'text'. Shell interprets what is between literally 
- Double quotes eg "text". Shell inteprets literally except using $ and backticks
- Backticks creates a 'shell-within-a-shell'. Useful for calling command-line programs. ie shell runs the command and captures STDOUT back into a variable
- Alternative to backticks ie Parentheses 

---

## What I Built / Practiced

- now_var='NOW'
- now_var_single='$now_var'
- now_var_double="$now_var"
- echo $now_var_single
- echo $now_var_double
- returns
  $now_var
  NOW
- The single quotes doesnt understand the variable call while the double quotes returns the NOW text
- For backticks
- rightnow_double="The date is `date`."
- echo $rightnow_double
- it returns The date is Fri 24 Dec 2026 13:35:35
- which is the current date and time.
- Using the parentheses
- rightnow_parenth="The date is $(date)."
- echo $rightnow_parenth
- returns the current date and time 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- backticks method is more backward compatible as it is older. The parentheses method is more modern 
  

---

## Resources

- Datacamp Introduction to Bash Scripting 

---

## Output

(Include links, screenshots, code snippets, or results)
