# Day 30 - Functions in Bash

## Objective

What was the goal for today?

Bash Functions

---

## What I Learned

- syntax function_name () {
-   function code
-   return something
- }
Second method.
- syntax function function_name {
-   function code
-   return something
- }

- To call a function type the function name
  

---

## What I Built / Practiced

- function print_hello() {
-   echo "Hell world!"
- }

- print_hello

- temp_f=30
- function convert_temp() {
-   temp_c=$(echo "scale=2; ($temp_f -32) * 5 / 9" | bc)
-   echo $temp_c
-   }

-   convert_temp

-   what_day_is_it() {
-    current_day=$(date | cut -d " " -f1)
-    echo $current_day
- }

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Functions allow reusable section of code that reduces repetition.
- 

---

## Resources

- Datacamp Introduction to Bash Scripting

---

## Output

(Include links, screenshots, code snippets, or results)
