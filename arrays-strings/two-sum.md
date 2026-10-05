# Two Sum

- **Difficulty:** Easy
- **LeetCode:** https://leetcode.com/problems/two-sum/

## Approach

Use two nested loops to check every pair of elements.
If the sum of two elements equals the target, return their indices.

## Time Complexity

O(n²)

## Space Complexity

O(1)

## Test Cases

### Test Case 1 — Typical
Input: nums = [2,7,11,15], target = 9
Output: [0,1]

### Test Case 2 — Edge
Input: nums = [3,3], target = 6
Output: [0,1]

## Notes / Edge Cases

- The same element cannot be used twice.
- Exactly one valid answer exists.
- The array can contain duplicate values.