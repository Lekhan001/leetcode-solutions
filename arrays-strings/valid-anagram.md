# Valid Anagram

## Problem
**LeetCode 242 - Valid Anagram**

**Difficulty:** Easy

**LeetCode:** https://leetcode.com/problems/valid-anagram/

## Approach
Use a frequency array of size 256.

- Count each character in string `s`.
- Decrease the count for each character in string `t`.
- If all counts are zero, the strings are anagrams.
- Otherwise, they are not anagrams.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Test Cases
1. `s = "anagram", t = "nagaram"` → `true`
2. `s = "rat", t = "car"` → `false`

## Notes / Edge Cases
- Both strings must contain the same characters with the same frequencies.
- Different character frequencies result in `false`.