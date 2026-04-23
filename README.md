# my-learning-journey
Create a function named values that receives a list as an argument and prints all of the items in the list one after the other.

For example, if the list is [1, 3, 5, 7], the output should be:

1

3

5

7

Important: The list is already provided to the function as the parameter lst. You don't need to read input or create the list — it is already passed as an argument when the function is called. This means inside your function, lst refers to the list you need to iterate through. You don't need to call the function — it is called automatically.

To iterate over a list and print each element, use the len() function inside the range() function:

def values(lst):
    for i in range(len(lst)):
        print(lst[i])
This way, i will iterate from 0 to len(lst) (not including), which covers exactly all of the list indices. lst[i] accesses the element at index i, and print() displays it on its own line.

