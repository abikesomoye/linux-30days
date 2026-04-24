# Day 25 - Numeric Variables

## Objective

What was the goal for today?
expr, bc command
---

## What I Learned

- expr is used for basic arithmetic eg expr 1 + 4 returns 5
- expr has a big limitation, it cannot handle decimal places eg expr 1 + 2.5 returns expr: not a decimal number: '2.5'
- Use basic calculator instead. Its a useful command-line program. To invoke it, type bc. Then type 5 + 7.5 returns 12.5. type quit to exit the basic calculator
- To use bc without opening the calculator, do this
- echo "5 +7.5" | bc
- bc has an argument scale which specifies the number of decimal places.
- e.g. echo "scale=3; 10/3"|bc
- returns 3.333

---

## What I Built / Practiced

- model1=87.65
- model2=89.20
- echo "The total score is $(echo "model1 + model2" | bc)"
- echi "The average score is $(echo "($model1 + $model2)/2" | bc"
- returns
- The total score is 176.85
- The average score is 88

- Anothe example converting Fahrenheit to Celsius
- #!/usr/bash
- temp_f=$1
- #Subtract 32
- temp_f2=$(echo "scale=2; $temp_f -32" |bc)
- #Multiply by 5/9
- temp_c=$(echo "scale=2; $temp_f2 * 5 * 9" | bc)
- #Print the Celcius temperature
- echo $temp_c

- To run it bash script.sh 108

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Numbers are not natively built in to the shell like REPLs(console) such as R and Python
- 

---

## Resources

- Datacamp Introduction to Bash Scripting 

---

## Output

(Include links, screenshots, code snippets, or results)
