# Day 10 - [Topic]

## Objective

What was the goal for today?

Select columns and patterns from a file 

---

## What I Learned

- cut to select
- -f to select the field
- -d the delimiter
- grep to  search for patterns or text in a file
- grep common flags are
- -c counts matching lines
- -h hides the filename when searching multiple files
- -i ignores case
- -l prints the filenames that contain matches, not the matches
- -n prints line numbers for matching lines
- -v inverts the match, it shows lines that don't match

---

## What I Built / Practiced

- cut -f 8 -d , clients.csv this selects column 8 of the clients file whose delimiter is comma ,.
- grep female clients.csv this prints the lines matching female in the clients file
- grep -c female clients.csv this counts the number of lines that has female in the match
- grep -v female clients.csv this returns matches that dont have female in the match eg. male, binary 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- head and tail commands select rows
- cut selects columns
- grep select lines according to what matches they contain 

---

## Resources

- Datacamp Introduction to Shell 

---

## Output

(Include links, screenshots, code snippets, or results)
