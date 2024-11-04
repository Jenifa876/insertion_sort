# insertion_sort
This is a simple C++ program that implements the Insertion Sort algorithm. The program sorts an array of integers in ascending order and then prints the sorted array.

**Overview**

Insertion Sort is a comparison-based sorting algorithm. It builds the final sorted array one element at a time by repeatedly taking an element from the unsorted portion of the array and inserting it into the correct position in the sorted portion.

**Program Structure**

The program is divided into three main components:

insertionSort Function: Implements the Insertion Sort algorithm.
printArray Function: Prints the array elements.
main Function: Sets up the array, calls the sorting function, and displays the result.

**Algorithm Explanation**

Start from the second element (index 1) and iterate through the array.
Compare the current element with the elements in the sorted portion (left side) of the array.
If the current element is smaller, move the elements of the sorted portion to the right to make room.
Insert the current element at the correct position.
