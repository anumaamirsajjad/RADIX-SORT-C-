# RADIX-SORT-C-
C++ implementation of a generic Queue data structure using queue and a sorting algorithm : Radix Sort for integers and strings.



Features
Generic Queue Implementation:
A template-based Queue class that supports any data type, implemented using a singly linked list.
Supports basic operations: enqueue, dequeue, isEmpty, and display.


Radix Sort for Integers:
Sorts a list of integers based on their individual digits.
Users can specify the maximum number of digits and the total number of integers to sort.

Radix Sort for Strings:
Sorts a list of strings based on their characters.
Users can specify the maximum length of strings and the total number of strings to sort.
Handles case insensitivity by converting uppercase letters to lowercase.
Usage

Compile the Code: Use a C++ compiler that supports C++11 or higher.
Run the Program: The user will be prompted to enter the required parameters for sorting integers and strings.
Input Validation: The program checks for valid input values, ensuring that the numbers and strings meet specified constraints.
Output: Displays the sorted arrays of integers and strings.

Example
For integer sorting, the user inputs a series of integers, and the program sorts them based on their digits.
For string sorting, the user inputs a series of strings, which are sorted based on their characters, with padding added for shorter strings and case insensitivity handled.
This implementation demonstrates the use of templates in C++ for creating a flexible data structure, along with efficient sorting techniques suitable for various data types.
