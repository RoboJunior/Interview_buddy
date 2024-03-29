# Interview Buddy
The Interview package contains a Python class designed to assist with various common interview questions and algorithms. This class offers methods to perform tasks related to fundamental algorithms and data structures frequently encountered during technical interviews.

# Features:
## Fibonacci Series Calculation:

Computes the Fibonacci series up to a specified number.
## Palindrome Checking:

Determines whether a given string is a palindrome or not.
## Bubble Sort:

Sorts a list of elements using the Bubble Sort algorithm.
## Insertion Sort:

Sorts a list of elements using the Insertion Sort algorithm.
## Anagram Detection:

Checks if two strings are anagrams of each other.
## Binary Search:

Searches for an element in a sorted list using the Binary Search algorithm.
## Minimum and Maximum Value Detection:

Finds the minimum and maximum values in a list of elements.
## Array Reversal:

Reverses the order of elements in a list.
## Usage:
Instantiate the Interview class with the necessary data inputs, and call the respective methods to perform the desired operations. The class provides insightful print statements during execution for better understanding and debugging purposes.

## Example python code
## Example usage of the Interview class
interview_instance = Interview(data=[5, 3, 8, 2, 1])

## Compute Fibonacci series
interview_instance.fibonacci_series()

## Check for palindrome
is_palindrome = interview_instance.palindrom()
print("Is Palindrome:", is_palindrome)

## Sort using Bubble Sort
sorted_data = interview_instance.bubble_sort()
print("Sorted Data (Bubble Sort):", sorted_data)

## Find minimum value
min_value = interview_instance.min_()
print("Minimum Value:", min_value)

## Reverse the array
reversed_data = interview_instance.reverse()
print("Reversed Data:", reversed_data)

# Contribution:
Contributions, suggestions, and bug reports are welcome! Feel free to fork this repository, make changes, and submit pull requests.


## Documentation
This interview-buddy was developed for students and beginner who are struggling to learn the logic behind algorithms and datastructures just give your task it will give you the output with basic explanation of the code its being developed hope it helps

these are the commands used in it 

**Interview()** -> which has two parameter which changes according to your task if you are performing sorting you can simple pass on list,if your program needs two parameters you can pass them also for example binary search we need two parameters the input list and searching element like so 

there is **binary_search**,**bubble_sort**,**insertion sort**,**min_**,**max_**,**anagram**,**palindrom**,**fibonacci series** and looking forward to add more features to the package

[package](https://pypi.org/project/interview-buddy/0.1/#description) 📌


## Authors

- [@RoboJunior](https://github.com/RoboJunior) 👨‍💻




## Installation

Install interview-buddy with cmd

```bash
  pip install interview-buddy==0.1
```
    
