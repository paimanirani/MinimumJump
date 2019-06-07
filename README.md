# MinimumJump
There are so many ways to do this which you can find it online but my approach to get minimum number of jumps to reach end is easy and self explanatory.

Given an array of integers where each element represents the max number of steps that can be made to move forward. We need to get the elements along with the minimum number of jumps needed to reach the end of the array (starting from the first element). If an element is 0, then cannot move through that element.

Example:

Input: arr[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9}
Output: 3 (1-> 3 -> 8 ->9)
First element is 1, so can only go to 3. Second element is 3, so can make at most 3 steps eg to 5 or 8 or 9.
