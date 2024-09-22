# MergeSort Algorithm in C++

## Description
MergeSort is a highly efficient, comparison-based sorting algorithm that utilizes the divide-and-conquer approach. It works by dividing the array into two halves, recursively sorting each half, and merging them back together into a single sorted array. MergeSort is stable, meaning it maintains the relative order of equal elements, and is preferred for sorting linked lists due to its efficient merge operation.

MergeSort is often used in external sorting where the data is too large to fit into memory.

## Algorithm Overview
1. **Divide**: Split the array into two halves.
2. **Conquer**: Recursively apply MergeSort to each half until you have sub-arrays of size one.
3. **Combine**: Merge the two sorted halves back into a single sorted array.

### Steps in the Merge Operation:
- Compare the elements of the two halves.
- Place the smaller element in the new array.
- Repeat until all elements from both halves are merged.

## Code Explanation
- **merge function**: This function merges two sorted sub-arrays into one sorted array.
- **mergeSort function**: The recursive function that splits the array and calls the merge function to sort.
- **Driver code**: Handles input/output and initializes the sorting process.

## Time and Space Complexity
- **Time Complexity**:
  - **Best case**: `O(n log n)`
  - **Average case**: `O(n log n)`
  - **Worst case**: `O(n log n)`
  
- **Space Complexity**: `O(n)` – Additional memory is required for merging the two halves.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MergeSort.git
