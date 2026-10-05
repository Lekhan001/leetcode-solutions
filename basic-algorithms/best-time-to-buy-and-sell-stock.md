# Best Time to Buy and Sell Stock

## Problem
**LeetCode 121 - Best Time to Buy and Sell Stock**

**Difficulty:** Easy

**LeetCode:** https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

## Approach
Track the minimum price seen so far and calculate the profit if the stock is sold on each day.

- Start with the first price as the minimum price.
- Update the minimum price when a lower price is found.
- Calculate the profit using the current price and minimum price.
- Keep the maximum profit found.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Test Cases
1. `prices = [7,1,5,3,6,4]` → `5`
2. `prices = [7,6,4,3,1]` → `0`

## Notes / Edge Cases
- If prices continuously decrease, the maximum profit is `0`.
- Only one buy and one sell are allowed.
- The buy must happen before the sell.