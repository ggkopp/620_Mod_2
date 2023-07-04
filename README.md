# Python Data Structures and Notebooks

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

Student Name: Garrett Kopp

My Repo: https://github.com/ggkopp/620_Mod_2

## Rubric

Each question is worth one point.

1. Modify the Markdown cell above to put your name after "Student Name:"; you will be expected to do this in all assignments presented in this format for this class.

2. Write code that divides any two numbers, stores the result in a variable, and prints the result with an appropriate label.

3. Using loops (and potentially conditionals), write Python code that prints the factorial of each integer from 1 through 10 (which you can store in a variable if you want). The factorial of an integer is the product of all of the integers of 1 through the number. Print the result with an appropriate label.

4. Write a python function that takes a single parameter and calculates and returns the average (mean) of the values in the parameter (which you may assume is iterable).  Show that your function works by printing the result of calling the function on the list in the cell below.

5. Using your mean function above, write a function that calculates the variance of the list of numbers (see https://en.wikipedia.org/wiki/Variance for more information on the formula). In short:
* subtract the mean of the elements in the list from every element in the list; store these values in a new list
* square every element in the new list and sum the elements together
* divide the resulting number by N (where N is the length of the original list)

Show the result of calling your function in the lists in the code cell. You must use one or more list comprehensions or map/filter in your code.

6. Create a list with at least 15 elements in it. Use list slicing to print the following:
* The first 5 elements of the list
* The last 5 elements of the list
* The list reversed (hint, show the entire list with a stride of -1)
* Every second element in the list
* Every third element in the list (stride of 3)

7. Build a dictionary that contains the following information about this class (with appropriate names as keys):
* The name
* The course number
* The semester/term in which you are taking this course
* The number of credit hours this course counts for
* A list of the course learning objectives

The majority of this information can be found in the syllabus. Print the dictionary.

8.  Given the dictionary defined in the code cell below, print the list of level 3 spells the character has.

9. Write code to determine the number of unique elements in the list below.  You MUST use a set in finding your solution.  Print the number of unique values in the list with an appropriate label.

10. Create a new Jupyter Notebook (the name of the notebook should be your S number). Add a Markdown cell that contains your name. Add a Code cell and write Python that uses loops to draw the following pattern:

```
*      *
**    **
***  ***
********
```
Make sure to add and submit both the new notebook and the changes to this notebook for this assignment.
