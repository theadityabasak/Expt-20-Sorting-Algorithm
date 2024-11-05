# Expt-20-Sorting-Algorithm
# App used: VS Code
# Theory
## Sorting ALgorithms Defination:
A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure. For Example: The below list of characters is sorted in increasing order of their ASCII values. That is, the character with a lesser ASCII value will be placed first than the character with a higher ASCII value. Sorting refers to rearrangement of a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure. Sorting means reordering of all the elements either in ascending or in descending order.

## Properties of the Sorting Algorithm
Sorting algorithms can be characterized by several properties that help evaluate their efficiency and suitability for different tasks. Here are the key properties:

1.Time Complexity:
Best Case: Minimum time taken for a sorted input.
2. Average Case: Expected time taken for random inputs.
Worst Case: Maximum time taken for the least favorable input. Common complexities:
O(n log n): Merge Sort, Quick Sort (average case)
O(n²): Bubble Sort, Insertion Sort, Selection Sort (worst case)
3. Space Complexity:
The amount of extra memory required beyond the input data.
In-place sorting algorithms (like Quick Sort and Heap Sort) use O(1) or O(log n) additional space.
Out-of-place algorithms (like Merge Sort) require O(n) additional space.
4. Stability:
A stable sort maintains the relative order of records with equal keys.
Stable algorithms: Merge Sort, Insertion Sort.
Unstable algorithms: Quick Sort, Heap Sort.
5. Adaptability:
An adaptive sorting algorithm takes advantage of existing order in the input.
For example, Insertion Sort is adaptive and performs well on partially sorted arrays.
Comparison-Based vs Non-Comparison-Based:
Comparison-based sorts (like Quick Sort and Merge Sort) compare elements to determine order.
Non-comparison-based sorts (like Counting Sort and Radix Sort) use specific properties of the input data and can achieve better time complexities under certain conditions.
6. Iterative vs Recursive:
Some algorithms are naturally implemented recursively (like Merge Sort), while others can be implemented iteratively (like Bubble Sort).
7. Performance on Different Data Types:
Some algorithms perform better on specific types of data, such as nearly sorted data or data with many duplicates.

## Advantages of Sorting Algorithms:
Sorting algorithms offer several advantages that can greatly impact the efficiency and usability of data processing. Here are some key benefits:

Improved Search Efficiency:
Sorted data allows for faster search algorithms, such as binary search, which operates in O(log n) time compared to O(n) for linear search.
Simplified Data Management:
Sorting organizes data, making it easier to understand and analyze. It aids in data visualization and reporting.
Enhanced Performance in Other Algorithms:
Many algorithms, like merge algorithms and certain graph algorithms, perform better or are simpler to implement when data is sorted.
Facilitates Duplicate Removal:
Sorting can simplify the process of identifying and removing duplicates in datasets.
Data Integrity:
Sorted data can help in maintaining data integrity by allowing easier identification of outliers or anomalies.
Ease of Merging:
When merging datasets, having them sorted can simplify the merging process, leading to more efficient data handling.
Improved Performance in Databases:
Many database operations, like indexing, benefit from sorted data, leading to faster retrieval and processing times.
Better Memory Utilization:
Some sorting algorithms are in-place, meaning they require minimal additional memory, which is beneficial for memory-constrained environments.
Adaptability:
Certain algorithms (like Insertion Sort) are adaptive, meaning they perform better on partially sorted data, making them useful in dynamic scenarios.
Flexibility:
Various sorting algorithms are available, allowing you to choose one that best fits your specific data characteristics and performance requirements.

## Types of sorting
1. Bubble sort
2. Insertion sort
3. selection sort

# Algorithms
## Algorithm Insertion Sort:
Start from the second element:
Begin with the second element of the array (index 1). Assume the first element (index 0) is already sorted.

Store the current element:
Store the current element in a variable (e.g., current).

Find the correct position:
Compare current with the elements in the sorted portion (to its left).
Start from the element just before current and move backward:
If the current element is smaller than the compared element, shift the compared element one position to the right.

Insert the current element:
Once you find the correct position (where the compared element is less than or equal to current), insert current into this position.

Repeat:
Move to the next element and repeat the process until the entire array is sorted.

Output the sorted array:
After sorting, print the sorted array.

## Bubble Sort Algorithm
Start with the first element:
Begin with the first element of the array.

Compare adjacent elements:
For each pair of adjacent elements (from the beginning of the array), compare them.

Swap if necessary:
If the first element of the pair is greater than the second element, swap them.

Repeat for the entire array:
Continue this process for all pairs in the array. After one full pass, the largest element will "bubble up" to the end of the array.

Reduce the range:
After each complete pass through the array, the next largest element will be in its correct position. Thus, reduce the range of comparison for the next pass (ignore the last sorted elements).

Repeat until sorted:
Continue the process until you make a complete pass without any swaps, which means the array is sorted.

Output the sorted array:
After sorting, print the sorted array.

## Selection Sort Algorithm
Start with the first element:
Assume the first element of the array is the minimum.

Find the minimum element:
Loop through the unsorted portion of the array (starting from the current index) to find the smallest element.

Update the minimum index:
If you find an element smaller than the current minimum, update the index of the minimum element (min_index).

Swap:
After the inner loop completes, if the smallest element found is not at the current index, swap it with the element at the current index.

Move to the next position:
Repeat the process for the next index, treating it as the new starting point.

Finish when sorted:
Continue until you have gone through all the elements. By the end, the array will be sorted.

Output the sorted array:
After sorting, print the sorted array.

# Conclusion:
We learnt to use the concepts of Sorting Algorithm and types of Sorting Algorithm such as Insertion sort, bubble sort, selection sort.
