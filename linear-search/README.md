1. Linear Search
1. Definition

Linear Search is a searching algorithm that checks each element of the array one by one until the target element is found or the array ends.

It works on both sorted and unsorted arrays.

2. When to Use

When array size is small

When data is unsorted

When simplicity is more important than performance

When random access is not available (like linked list)

3. Rules of Linear Search

Start from index 0.

Compare each element with the target value.

If element matches target, return the index or value.

If end of array is reached and no match found, return "not found".

No sorting is required.

Works for both primitive types and objects (with proper comparison).

4. Time Complexity

Best Case: O(1)
Worst Case: O(n)
Average Case: O(n)

Because in worst case, you must check every element.

5. Common Mistakes

Not handling the case when element is not present.

Using wrong loop boundary (i <= length instead of i < length).

Forgetting to return after finding element.
