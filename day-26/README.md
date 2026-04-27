# Day 26 - Arrays

## Objective

What was the goal for today?

Learning to create and manipulate arrays in Bash 
---

## What I Learned

- There are 2 types of arrays in Bash
- 1 Numerical-Indexed array
- 2 Associative Arrays
- Numerical-index are also known as lists in Python or vectors in R
- Creating a numerical-indexed array, you can do the following
- a. declare -a my_first_array or
- b. my_first_array=(1 2 3)
- You can return all elements using array[@] eg my_array=(1 3 5 2)
- echo ${my_array[@]}
- To get the length of an array use the # symbol e.g. echo ${#my_array[@]}
- To return the 3rd element of an array
- echo ${my_array[2]} returns 5
- To change an element in an array
- e.g. my_array[0]=99
- You can slice or subset an array using array[@]:N:M
- N is the starting index and M indicates the number of elements to return e.g my_second_array=(15 20 300 42 23 2 4 33 54 67 66)
- echo ${my_second_array[@]:3:2] returns 42 23
- Append to an array using array+=(elements)
eg my_array+=(10)
echo ${my_array[@]}
returns 99 3 5 2 10
--- Associative arrays are key-value pairs like dictionary in Python. This is available in Bash 4 onwards.
  To create eg declare -A city_details
  city_details=([city_name]="New York" [population]=200000)
  To index echo ${city_details[city_name]}
  returns New York
Or you can create and assign elements in one command.
eg declare -A city_details=([city_name]="Dallas" [population]=1000000
To return all keys in any array use !
eg echo ${!city_details[@]}

## What I Built / Practiced

- 
- 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- Bash does not use commas to separate array elements, it uses spaces instead. eg my_array=(1, 2, 3) is not correct. my_array=(1 2 3) is correct
- 

---

## Resources

- Datacamp Introduction to Bash Scripting

---

## Output

(Include links, screenshots, code snippets, or results)
