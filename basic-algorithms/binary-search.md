# Binary Search

## Problem
**LeetCode 704 - Binary Search**

**Difficulty:** Easy

**LeetCode:** https://leetcode.com/problems/binary-search/

## Approach
Use binary search on the sorted array.

- Set `left` to the first index.
- Set `right` to the last index.
- Find the middle index.
- If the middle element equals the target, return its index.
- If the middle element is smaller than the target, search the right half.
- Otherwise, search the left half.
- Return `-1` if the target is not found.

## Time Complexity
O(log n)

## Space Complexity
O(1)

## Test Cases
1. `nums = [-1,0,3,5,9,12], target = 9` → `4`
2. `nums = [-1,0,3,5,9,12], target = 2` → `-1`

## Notes / Edge Cases
- The input array is sorted in ascending order.
- If the target does not exist, return `-1`.
- A single-element array should also be handled correctly.