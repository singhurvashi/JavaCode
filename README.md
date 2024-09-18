
1. Bubble Sort

Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted.
Time Complexity:

    Best Case: O(n) (already sorted array)
    Average Case: O(n²)
    Worst Case: O(n²)

Explanation:

    Inner Loop: Compares adjacent elements and swaps them if they are out of order.
    Outer Loop: Ensures that the process repeats until the array is sorted.
    Inefficiency: Due to repetitive comparisons and swaps, Bubble Sort is inefficient for large datasets.

2. Selection Sort

Selection Sort divides the array into a sorted and an unsorted region. It repeatedly selects the smallest (or largest) element from the unsorted region and swaps it with the first unsorted element.
Time Complexity:

    Best Case: O(n²)
    Average Case: O(n²)
    Worst Case: O(n²)




Explanation:

    Selection: The algorithm finds the smallest element in the unsorted part and moves it to the sorted part.
    Efficiency: Fewer swaps than Bubble Sort but still inefficient for large datasets due to nested loops.

3. Insertion Sort

Insertion Sort works by building a sorted array one element at a time. It takes each element and inserts it into its correct position within the already sorted part of the array.
Time Complexity:

    Best Case: O(n) (already sorted array)
    Average Case: O(n²)
    Worst Case: O(n²)




Explanation:

    Shifting Elements: It shifts elements of the sorted section to find the correct place for the new element.
    Efficient for Small Arrays: Performs well for small or partially sorted arrays but becomes inefficient with larger datasets.

4. Merge Sort

Merge Sort is a divide-and-conquer algorithm that splits the array into two halves, recursively sorts them, and then merges the sorted halves back together.
Time Complexity:

    Best Case: O(n log n)
    Average Case: O(n log n)
    Worst Case: O(n log n)




Explanation:

    Divide and Conquer: Divides the array into halves and recursively sorts each half.
    Efficiency: It has an excellent time complexity of O(n log n) but requires additional space for merging.

5. Quick Sort

Quick Sort also follows the divide-and-conquer approach. It selects a "pivot" element and partitions the array such that elements smaller than the pivot are on the left and those larger are on the right. Then, it recursively sorts the left and right partitions.
Time Complexity:

    Best Case: O(n log n)
    Average Case: O(n log n)
    Worst Case: O(n²) (when pivot is the smallest or largest element)


 
Explanation:

    Partitioning: The key operation is the partitioning step, which rearranges the array such that all elements less than the pivot come before it and all elements greater than the pivot come after it.
    Efficient for Large Arrays: Quick Sort is one of the fastest algorithms for large datasets, although its worst-case complexity is O(n²).

6. Heap Sort

Heap Sort uses a binary heap data structure. It first builds a max heap from the input array and then repeatedly extracts the largest element and rebuilds the heap.
Time Complexity:

    Best Case: O(n log n)
    Average Case: O(n log n)
    Worst Case: O(n log n)



Explanation:

    Binary Heap: It ensures the array is partially sorted by maintaining a max heap structure.
    Efficiency: Like Merge Sort and Quick Sort, Heap Sort has a time complexity of O(n log n) but it’s not as fast as Quick Sort in practice.

