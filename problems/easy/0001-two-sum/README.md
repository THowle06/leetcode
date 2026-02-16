# 1. Two Sum

**Difficulty:** Easy
**Topics:** Array, Hash Table

---

## 📝 Problem Summary

Given an array of integers `nums` and an integer `target`, return *indeces of the two numbers such that they add up to `target`*.

You may assume that each input would have ***exactly one solution***, and you may not use the *same* element twice.

You can return the answer in any order.

**Example 1:**

```text
Input: 
nums = [3,4,5,6], target = 7

Output: [0,1]
```

Exaplanation: `nums[0] + nums[1] == 7`, so we return `[0,1]`.

**Example 2:**

```text
Input: nums = [4,5,6], target = 10

Output: [0,2]
```

**Example 3:**

```text
Input: nums = [5,5], target = 10

Output: [0,1]
```

**Constraints:**

- `2 <= nums.length <= 1000`
- `-10,000,000 <= nums[i] <= 10,000,000`
- `-10,000,000 <= target <= 10,000,000`
- **Only one valid answer exists.**

## Complexity Analysis

Time complexity: O(n)

Space complexity: O(n)

- `n` is the number of elements in the `nums` list.
