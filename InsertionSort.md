# Project 1

**[22,27,16,2,18,6]** -> Insertion Sort

Write the stages of the above given sequence according to the sort type.

Write the Big-O notation.

Time Complexity: After the sequence is sorted, which of the following cases does the number 18 fall into? Write
* Average case: The number we are looking for is in the middle
* Worst case: The number we are looking for is at the end
* Best case: The number we are looking for is at the beginning of the array.


## Solution

* We find the smallest element of the given pattern and replace it with the first number. 

* What about more? We find the second smallest element and replace it with the 2nd row. 

* You see that the second element is the smallest, don't touch it!!!. 

* Jump to row 3 now. At 4, 5, the series is over. This is the basic working principle of insertion sort.

1-) **[2,27,16,22,18,6]** 

2-) **[2,6,16,22,18,27]**

3-) **[2,6,16,22,18,27]**

4-) **[2,6,16,18,22,27]** 

### We are done!

## Next one;

**[7,3,5,8,2,9,4,15,6]** Write the first 4 steps of the sequence according to the Selection Sort.

1-) **[2,3,5,8,7,9,4,15,6]**

2-) **[2,3,4,8,7,9,5,15,6]**

3-) **[2,3,4,5,7,9,8,15,6]**

4-) **[2,3,4,5,6,9,8,15,7]**

```
continue...
