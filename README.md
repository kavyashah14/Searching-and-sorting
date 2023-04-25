# Searching-and-sorting
# Bubble sort

Bubble sort is a sorting algorithm that compares two adjacent elements and swaps them until they are in the intended order.
Just like the movement of air bubbles in the water that rise up to the surface, each element of the array move to the end in each iteration. Therefore, it is called a bubble sort.

# Selection sort
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted. One variation of selection sort is called “Bidirectional selection sort” which goes through the list of elements by alternating between the smallest and largest element, this way the algorithm can be faster in some cases.

# Insertion Sort
Insertion sort is an algorithm used to sort a collection of elements in ascending or descending order. The basic idea behind the algorithm is to divide the list into two parts: a sorted part and an unsorted part.
Initially, the sorted part contains only the first element of the list, while the rest of the list is in the unsorted part. The algorithm then iterates through each element in the unsorted part, picking one at a time, and inserts it into its correct position in the sorted part.
To do this, the algorithm compares the current element with each element in the sorted part, starting from the rightmost element. It continues to move to the left until it finds an element that is smaller (if sorting in ascending order) or larger (if sorting in descending order) than the current element.
Once the correct position has been found, the algorithm shifts all the elements to the right of that position to make room for the current element, and then inserts the current element into its correct position.

# Binary Search
Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 

Conditions for when to apply Binary Search in a Data Structure:
To apply binary search in any data structure, the data structure must maintain the following properties:

1. The data structure must be sorted.
2. Access to any element of the data structure takes constant time.

# Linear search
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.

How Linear Search Works?

Step 1: First, read the search element (Target element) in the array.

Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.

Step 3: Match the key with arr[i].

Step 4: If the key matches, return the index. Otherwise, increment i by 1.
