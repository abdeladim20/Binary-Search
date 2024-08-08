# Binary-Search

####
The BinarySearch function takes a sorted slice of integers arr and a target value target as input.
It initializes two pointers, low and high, to the start and end of the slice, respectively.
The function repeatedly calculates the midpoint mid of the current search range and compares the value at mid to the target.
If the values match, the function returns the index mid and a boolean indicating successful search (true).
If the value at mid is less than the target, the function updates low to mid + 1 and continues the search.
If the value at mid is greater than the target, the function updates high to mid - 1 and continues the search.
If the search range becomes empty (i.e., low > high), the function returns -1 and false, indicating that the target was not found.
Notes
###
This implementation assumes the input slice is sorted in ascending order.
The sort.Ints function is used to ensure the array is sorted before searching.
You can modify the main function to test the binary search with different inputs and target values.
This example demonstrates a basic binary search algorithm in Go. You can extend or modify this code to suit your specific use case.