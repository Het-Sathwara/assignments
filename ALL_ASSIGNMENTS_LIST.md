# Python Assignments: Detailed List of All Assignment Questions

---

## Control Flow Assignments
### Conditional Statements
- **Assignment 1:** Write a program that asks the user to input a number and prints whether the number is positive.
- **Assignment 2:** Write a program that asks the user to input a number and prints whether the number is positive or negative.
- **Assignment 3:** Write a program that asks the user to input a number and prints whether the number is positive, negative, or zero.
- **Assignment 4:** Write a program that asks the user to input a number and prints whether the number is positive and even, positive and odd, or negative.

### Loops
- **Assignment 5:** Write a program that prints all the numbers from 1 to 10 using a for loop.
- **Assignment 6:** Write a program that prints all the numbers from 1 to 10 using a while loop.
- **Assignment 7:** Write a program that prints a 5x5 grid of asterisks (*) using nested loops.
- **Assignment 8:** Write a program that asks the user to input numbers until they input 0. The program should print the sum of all the input numbers.
- **Assignment 9:** Write a program that prints all the numbers from 1 to 10 except 5 using a for loop and continue statement.
- **Assignment 10:** Write a program that defines an empty function using the pass statement.
- **Assignment 11:** Write a program that asks the user to input a number and prints all the even numbers from 1 to that number using a for loop.
- **Assignment 12:** Write a program that calculates the factorial of a number input by the user using a while loop.
- **Assignment 13:** Write a program that calculates the sum of the digits of a number input by the user using a while loop.
- **Assignment 14:** Write a program that checks if a number input by the user is a prime number using a for loop.
- **Assignment 15:** Write a program that prints the first n Fibonacci numbers, where n is input by the user.

---

## Lists Assignments
- **Assignment 1:** Create a list of the first 20 positive integers. Print the list.
- **Assignment 2:** Print the first, middle, and last elements of the list created in Assignment 1.
- **Assignment 3:** Print the first five elements, the last five elements, and the elements from index 5 to 15 of the list created in Assignment 1.
- **Assignment 4:** Create a new list containing the squares of the first 10 positive integers using a list comprehension. Print the new list.
- **Assignment 5:** Create a new list containing only the even numbers from the list created in Assignment 1 using a list comprehension. Print the new list.
- **Assignment 6:** Create a list of random numbers and sort it in ascending and descending order. Remove the duplicates from the list and print the modified list.
- **Assignment 7:** Create a nested list representing a 3x3 matrix and print the matrix. Access and print the element at the second row and third column.
- **Assignment 8:** Create a list of dictionaries where each dictionary represents a student with keys 'name' and 'score'. Sort the list of dictionaries by the 'score' in descending order and print the sorted list.
- **Assignment 9:** Write a function that takes a 3x3 matrix (nested list) as input and returns its transpose. Print the original and transposed matrices.
- **Assignment 10:** Write a function that takes a nested list and flattens it into a single list. Print the original and flattened lists.
- **Assignment 11:** Create a list of the first 10 positive integers. Remove the elements at indices 2, 4, and 6, and insert the element '99' at index 5. Print the modified list.
- **Assignment 12:** Create two lists of the same length. Use the `zip` function to combine these lists into a list of tuples and print the result.

---

## Dictionaries Assignments
- **Assignment 1:** Create a dictionary with the first 10 positive integers as keys and their squares as values. Print the dictionary.
- **Assignment 2:** Print the value of the key 5 and the keys of the dictionary created in Assignment 1.
- **Assignment 3:** Add a new key-value pair (11, 121) to the dictionary created in Assignment 1 and then remove the key-value pair with key 1. Print the modified dictionary.
- **Assignment 4:** Iterate over the dictionary created in Assignment 1 and print each key-value pair.
- **Assignment 5:** Create a new dictionary containing the cubes of the first 10 positive integers using a dictionary comprehension. Print the new dictionary.
- **Assignment 6:** Create two dictionaries: one with keys as the first 5 positive integers and values as their squares, and another with keys as the next 5 positive integers and values as their squares. Merge these dictionaries into a single dictionary and print it.
- **Assignment 7:** Create a nested dictionary representing a student with keys 'name', 'age', 'grades', where 'grades' is another dictionary with keys 'math', 'science', and 'english'. Print the nested dictionary.
- **Assignment 8:** Create a dictionary where the keys are the first 5 positive integers and the values are lists containing the first 5 multiples of the key. Print the dictionary.
- **Assignment 9:** Create a dictionary where the keys are the first 5 positive integers and the values are tuples containing the key and its square. Print the dictionary.
- **Assignment 10:** Create a dictionary with the first 5 positive integers as keys and their squares as values. Convert the dictionary to a list of tuples and print it.
- **Assignment 11:** Create a dictionary with the first 10 positive integers as keys and their squares as values. Create a new dictionary containing only the key-value pairs where the key is even. Print the new dictionary.
- **Assignment 12:** Create a dictionary with the first 5 positive integers as keys and their squares as values. Create a new dictionary with keys and values swapped. Print the new dictionary.

---

## Exception Handling Assignments
- **Assignment 1:** Write a function that takes two integers as input and returns their division. Use try, except, and finally blocks to handle division by zero and print an appropriate message.
- **Assignment 2:** Write a function that reads the contents of a file named `data.txt`. Use try, except, and finally blocks to handle file not found errors and ensure the file is properly closed.
- **Assignment 3:** Write a function that takes a list of integers and returns their sum. Use try, except, and finally blocks to handle TypeError if a non-integer value is encountered and print an appropriate message.
- **Assignment 4:** Write a function that prompts the user to enter an integer. Use try, except, and finally blocks to handle ValueError if the user enters a non-integer value and print an appropriate message.
- **Assignment 5:** Write a function that takes a dictionary and a key as input and returns the value associated with the key. Use try, except, and finally blocks to handle KeyError if the key is not found in the dictionary and print an appropriate message.
- **Assignment 6:** Write a function that performs nested exception handling. It should first attempt to convert a string to an integer, and then attempt to divide by that integer. Use nested try, except, and finally blocks to handle ValueError and ZeroDivisionError and print appropriate messages.
- **Assignment 7:** Write a function that takes a list and an index as input and returns the element at the given index. Use try, except, and finally blocks to handle IndexError if the index is out of range and print an appropriate message.
- **Assignment 8:** Write a function that attempts to open a URL and read its contents. Use try, except, and finally blocks to handle network-related errors and print an appropriate message.
- **Assignment 9:** Write a function that attempts to parse a JSON string. Use try, except, and finally blocks to handle JSONDecodeError if the string is not a valid JSON and print an appropriate message.
- **Assignment 10:** Define a custom exception named `NegativeNumberError`. Write a function that raises this exception if a negative number is encountered in a list. Use try, except, and finally blocks to handle the custom exception and print an appropriate message.
- **Assignment 11:** Write a function that calls another function which may raise an exception. Use try, except, and finally blocks to handle the exception and print an appropriate message.
- **Assignment 12:** Define a class with a method that performs a division operation. Use try, except, and finally blocks within the method to handle division by zero and print an appropriate message.

---

## Advanced Functions Assignments
- **Assignment 1:** Define a recursive function to calculate the nth Fibonacci number using memoization. Test the function with different inputs.
- **Assignment 2:** Define a function that takes two arguments, a and b, where b is a dictionary with a default value of an empty dictionary. The function should add a new key-value pair to the dictionary and return it. Test the function with different inputs.
- **Assignment 3:** Define a function that takes a variable number of keyword arguments and returns a dictionary containing only those key-value pairs where the value is an integer. Test the function with different inputs.
- **Assignment 4:** Define a function that takes another function as a callback and a list of integers. The function should apply the callback to each integer in the list and return a new list with the results. Test with different callback functions.
- **Assignment 5:** Define a function that returns another function. The returned function should take an integer and return its square. Test the returned function with different inputs.
- **Assignment 6:** Define a function that calculates the time taken to execute another function. Apply this decorator to a function that performs a complex calculation. Test the decorated function with different inputs.
- **Assignment 7:** Define a higher-order function that takes two functions, a filter function and a map function, along with a list of integers. The higher-order function should first filter the integers using the filter function and then apply the map function to the filtered integers. Test with different filter and map functions.
- **Assignment 8:** Define a function that composes two functions, f and g, such that the result is f(g(x)). Test with different functions f and g.
- **Assignment 9:** Use the functools.partial function to create a new function that multiplies its input by 2. Test the new function with different inputs.
- **Assignment 10:** Define a function that takes a list of integers and returns their average. The function should handle any errors that occur (e.g., empty list) and return None in such cases. Test with different inputs.
- **Assignment 11:** Define a function that generates an infinite sequence of Fibonacci numbers. Test by printing the first 10 numbers in the sequence.
- **Assignment 12:** Define a curried function that takes three arguments, one at a time, and returns their product. Test the function by providing arguments one at a time.

---

## Logging Assignments
- **Assignment 1:** Write a Python function to create a basic logger that logs messages to a file named `app.log`. Modify the function to log messages of levels: DEBUG, INFO, WARNING, ERROR, and CRITICAL.
- **Assignment 2:** Write a Python function to create a logger that logs messages to both a file named `app.log` and the console. Modify the function to use different logging levels for the file and console handlers.
- **Assignment 3:** Write a Python function to create a logger with a custom log message format that includes the timestamp, logging level, and message. Modify the function to use different formats for the file and console handlers.
- **Assignment 4:** Write a Python function to create a logger that uses a rotating file handler, which creates a new log file when the current log file reaches a certain size. Modify the function to keep a specified number of backup log files.
- **Assignment 5:** Write a Python function that logs an exception stack trace to a log file when an exception occurs. Modify the function to log the stack trace at the ERROR level.
- **Assignment 6:** Write a Python function to create a logger that includes contextual information (e.g., function name, line number) in the log messages. Modify the function to include additional contextual information (e.g., user ID, session ID).
- **Assignment 7:** Write a Python function to configure logging using a dictionary. The configuration should include handlers for both file and console logging. Modify the dictionary to include different logging levels and formats for each handler.
- **Assignment 8:** Write a Python script that sets up logging for a multi-module application. Each module should have its own logger. Modify the script to propagate log messages from each module's logger to a root logger that handles logging to a file.
- **Assignment 9:** Write a Python script to benchmark the performance of logging with different handlers (e.g., file handler, console handler, rotating file handler). Modify the script to compare the performance of logging with and without message formatting.

---

## NumPy Assignments
- **Assignment 1:** Create a NumPy array of shape (5, 5) filled with random integers between 1 and 20. Replace all the elements in the third column with 1. Create a NumPy array of shape (4, 4) with values from 1 to 16. Replace the diagonal elements with 0.
- **Assignment 2:** Create a NumPy array of shape (6, 6) with values from 1 to 36. Extract the sub-array consisting of the 3rd to 5th rows and 2nd to 4th columns. Create a NumPy array of shape (5, 5) with random integers. Extract the elements on the border.
- **Assignment 3:** Create two NumPy arrays of shape (3, 4) filled with random integers. Perform element-wise addition, subtraction, multiplication, and division. Create a NumPy array of shape (4, 4) with values from 1 to 16. Compute the row-wise and column-wise sum.
- **Assignment 4:** Create a NumPy array of shape (5, 5) filled with random integers. Compute the mean, median, standard deviation, and variance of the array. Create a NumPy array of shape (3, 3) with values from 1 to 9. Normalize the array (i.e., scale the values to have a mean of 0 and a standard deviation of 1).
- **Assignment 5:** Create a NumPy array of shape (3, 3) filled with random integers. Add a 1D array of shape (3,) to each row of the 2D array using broadcasting. Create a NumPy array of shape (4, 4) filled with random integers. Subtract a 1D array of shape (4,) from each column of the 2D array using broadcasting.
- **Assignment 6:** Create a NumPy array of shape (3, 3) representing a matrix. Compute its determinant, inverse, and eigenvalues. Create two NumPy arrays of shape (2, 3) and (3, 2). Perform matrix multiplication on these arrays.
- **Assignment 7:** Create a NumPy array of shape (3, 3) with values from 1 to 9. Reshape the array to shape (1, 9) and then to shape (9, 1). Create a NumPy array of shape (5, 5) filled with random integers. Flatten the array and then reshape it back to (5, 5).
- **Assignment 8:** Create a NumPy array of shape (5, 5) filled with random integers. Use fancy indexing to extract the elements at the corners of the array. Create a NumPy array of shape (4, 4) filled with random integers. Use boolean indexing to set all elements greater than 10 to 10.
- **Assignment 9:** Create a structured array with fields 'name' (string), 'age' (integer), and 'weight' (float). Add some data and sort the array by age. Create a structured array with fields 'x' and 'y' (both integers). Add some data and compute the Euclidean distance between each pair of points.

---

## Pandas Assignments
- **Assignment 1:** Create a Pandas DataFrame with 4 columns and 6 rows filled with random integers. Set the index to be the first column. Create a Pandas DataFrame with columns 'A', 'B', 'C' and index 'X', 'Y', 'Z'. Fill the DataFrame with random integers and access the element at row 'Y' and column 'B'.
- **Assignment 2:** Create a Pandas DataFrame with 3 columns and 5 rows filled with random integers. Add a new column that is the product of the first two columns. Create a Pandas DataFrame with 3 columns and 4 rows filled with random integers. Compute the row-wise and column-wise sum.
- **Assignment 3:** Create a Pandas DataFrame with 3 columns and 5 rows filled with random integers. Introduce some NaN values. Fill the NaN values with the mean of the respective columns. Create a Pandas DataFrame with 4 columns and 6 rows filled with random integers. Introduce some NaN values. Drop the rows with any NaN values.
- **Assignment 4:** Create a Pandas DataFrame with 2 columns: 'Category' and 'Value'. Fill the 'Category' column with random categories ('A', 'B', 'C') and the 'Value' column with random integers. Group the DataFrame by 'Category' and compute the sum and mean of 'Value' for each category. Create a Pandas DataFrame with 3 columns: 'Product', 'Category', and 'Sales'. Fill the DataFrame with random data. Group the DataFrame by 'Category' and compute the total sales for each category.
- **Assignment 5:** Create two Pandas DataFrames with a common column. Merge the DataFrames using the common column. Create two Pandas DataFrames with different columns. Concatenate the DataFrames along the rows and along the columns.
- **Assignment 6:** Create a Pandas DataFrame with a datetime index and one column filled with random integers. Resample the DataFrame to compute the monthly mean of the values. Create a Pandas DataFrame with a datetime index ranging from '2021-01-01' to '2021-12-31' and one column filled with random integers. Compute the rolling mean with a window of 7 days.
- **Assignment 7:** Create a Pandas DataFrame with a MultiIndex (hierarchical index). Perform some basic indexing and slicing operations on the MultiIndex DataFrame. Create a Pandas DataFrame with MultiIndex consisting of 'Category' and 'SubCategory'. Fill the DataFrame with random data and compute the sum of values for each 'Category' and 'SubCategory'.
- **Assignment 8:** Create a Pandas DataFrame with columns 'Date', 'Category', and 'Value'. Create a pivot table to compute the sum of 'Value' for each 'Category' by 'Date'. Create a Pandas DataFrame with columns 'Year', 'Quarter', and 'Revenue'. Create a pivot table to compute the mean 'Revenue' for each 'Quarter' by 'Year'.
- **Assignment 9:** Create a Pandas DataFrame with 3 columns and 5 rows filled with random integers. Apply a function that doubles the values of the DataFrame. Create a Pandas DataFrame with 3 columns and 6 rows filled with random integers. Apply a lambda function to create a new column that is the sum of the existing columns.
