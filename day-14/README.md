# Day 14 - Sort Command

## Objective

What was the goal for today?

Sort Lines of Text 

---

## What I Learned

- flag -n sorts numerically
- flag -r reverses the sort
- flag -b ignores blank spaces
- flag -f case insensitive

---

## What I Built / Practiced

- sort -n | head -n 1 prints the largest value
- cut -d , -f 2 seasonal/winter.csv | grep -v Tooth | sort -r sorts the result in descending order
- cut -d , -f 2 seasonal/winter.csv | grep -v Tooth | sort | uniq -c this removes adjacent duplicates in the result and counts

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Usually pipelines often use grep to remove unwanted records while sort puts the records in order


---

## Resources

- Datacamp Introduction to Shell

---

## Output

(Include links, screenshots, code snippets, or results)
