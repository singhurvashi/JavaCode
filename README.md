Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted.
Time Complexity:

    Best Case: O(n) (already sorted array)
    Average Case: O(n²)
    Worst Case: O(n²)

    Explanation:

    Inner Loop: Compares adjacent elements and swaps them if they are out of order.
    Outer Loop: Ensures that the process repeats until the array is sorted.
    Inefficiency: Due to repetitive comparisons and swaps, Bubble Sort is inefficient for large datasets.