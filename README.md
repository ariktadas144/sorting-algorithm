# sorting-algorithm

Time complexity analysis of performance of Bubble Sort compared to other sorting algorithms using time complexity analysis <br/><br/>
<b>1. Bubble Sort </b>

Best Case: O(n) (if optimized with an early termination flag)<br/>
Average Case: O(n^2)<br/>
Worst Case: O(n^2)<br/><br/>
Space Complexity: 
O(1) (in-place sorting)<br/>
Stable Sort: Yes (preserves order of equal elements)<br/>
Performance: Very slow for large inputs due to quadratic time complexity. Only useful for educational purposes or very small datasets.
<br/><br/>
<b>2. Selection Sort</b><br/><br/>
Best Case: O(n^2)<br/>
Average Case: O(n^2)<br/>
Worst Case: O(n^2)<br/><br/>
Space Complexity: O(1)<br/>
Stable Sort: No (swaps non-adjacent elements)<br/>
Performance: Similar to Bubble Sort but performs fewer swaps, making it slightly better in practice.<br/><br/>

<b>3. Insertion Sort</b><br/><br/>
Best Case: O(n) (already sorted)
Average Case: O(n^2)
Worst Case: O(n^2)<br/><br/>
Space Complexity: O(1)<br/>
Stable Sort: Yes<br/>
Performance: Faster than Bubble and Selection Sort in practice, especially for nearly sorted data.<br/><br/>

<b>4. Merge Sort (Divide and Conquer)</b><br/><br/>
Best Case: O(nlogn)<br/>
Average Case: O(nlogn)<br/>
Worst Case: O(nlogn)<br/><br/>
Space Complexity: O(n) (not in-place)<br/>
Stable Sort: Yes<br/>
Performance: Much faster than O(n^2) sorts for large datasets but requires extra space. <br/><br/>

<b>5. Quick Sort (Divide and Conquer)</b><br/><br/>
Best Case: O(nlogn)<br/>
Average Case: O(nlogn)<br/>
Worst Case: O(n^2) (rare, occurs when pivot is always the smallest/largest element)<br/><br/>
Space Complexity: O(logn) (in-place sorting)<br/>
Stable Sort:  No<br/>
Performance: One of the fastest sorting algorithms in practice, especially with a good pivot selection (like median-of-three).<br/><br/>

<b>6. Heap Sort</b><br/><br/>
Best Case: O(nlogn)<br/>
Average Case: O(nlogn)<br/>
Worst Case: O(nlogn) <br/><br/>
Space Complexity: O(1) (in-place sorting)<br/>
Stable Sort: No<br/>
Performance: Consistently O(nlogn), but slower than Quick Sort in practice due to heap operations. Useful when stability isn't required and extra space is limited.
