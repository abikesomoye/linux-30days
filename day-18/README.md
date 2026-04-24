# Day 18 - Using $@ and $1 $2

## Objective

What was the goal for today?

Passing filenames to scripts

---

## What I Learned

- using $@ to pass filenames not included in the file script
- Adding  parameters using $ dollar sign eg $1 $2 


---

## What I Built / Practiced

- nano count-records.sh
- tail -q -n +2 $@ | wc -l
- bash count-records.sh seasonal/*.csv > num-records.out
- Another example cut -d , -f 1 $2 $1
- bash num.sh 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- You can use $@ to pass filenames that are not included in the shell script
- add the filenames when running the programme such as bash uniq-lines.sh seasonal/summer.csv

---

## Resources

- Datacamp Introduction to Shell

---

## Output

(Include links, screenshots, code snippets, or results)
