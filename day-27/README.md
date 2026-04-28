# Day 27 - IF Statements 

## Objective

What was the goal for today?

---

## What I Learned

- syntax : if [condition]; then
-              #code
-          else
-              #code
-          fi

- Flags
- -eq means equal to
- -ne means not equal to
- -lt means less than
- -le means less than or equalnto
- -gt means greater than
- -ge means greater than or equal to

- Other file related flags
- -e means if the file exists
- -s means if the file exists and has size greater than zero
- -r means if the file exists and is readable
- -w means if the file exists and is writable 

- AND notation uses &&
- OR notation uses ||


---

## What I Built / Practiced

- x="Queen"
- if [ $x == "King" ]; then
-    echo "$x is a King!"
- else
-    echo "$x is not a king"
- fi

- x=10
- if (($x > 5)); then
-   echo "$x is more than 5!"
- fi

- Using flags
- x=10
- if [ $x -gt 5]; then
-   echo "$x is more than 5!"
- fi

- x=10
- if [ $x -gt 5 ] && [ $x -lt 11]; then
-   echo "$x is more than 5 and less than 11!"
- fi

-   Using the double square brackets notation
-   x=10
-   if [[ $x -gt 5 && $x -lt 11 ]]; then
-   echo "$x is more than 5 and less than 11!"
-   fi

-   if grep -q Hello words.txt; then
-     echo "Hello is inside"
-   fi

- can also be rewritten
-  if $(grep -q Hello words.txt); then
-    echo "Hello is inside"
-  fi

---

## Challenges Faced

- 
- 

---

## Key Takeaways

-  Spaces are required between square brackets and conditional elements.
-  Always add ; after the close bracket 
- 

---

## Resources

- Datacamp Introduction to Bash Scripting

---

## Output

(Include links, screenshots, code snippets, or results)
