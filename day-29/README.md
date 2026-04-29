# Day 29 - Case Statements 

## Objective

What was the goal for today?
 Learning CASE statements 

---

## What I Learned

- Basic CASE format
- case 'STRINGVAR' in
- PATTERN1)
- COMMAND1;;
- PATTERN2)
- COMMAND2;;
- *)
- DEFAULT COMMAND;;
- esac
- 
- 

---

## What I Built / Practiced

- case $(cat $1) in
-   *syndey*)
-   mv $1 sydney/ ;;
-   *melbourne*|*brisbane*)
-   rm $1 ;;
-   *canberra*)
-   mv $1 "IMPORTANT_$1" ;;
---

## Challenges Faced

- 
- 

---

## Key Takeaways

- CASE statements help create ckearer and more efficient code in cases of complex or multiple IF statementsg
- 

---

## Resources

- 

---

## Output

(Include links, screenshots, code snippets, or results)
