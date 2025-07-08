# 🧠 Day 4 - 21 Day DSA Challenge

## ✅ Problem Statement

**Find the Duplicate Number**

Given an array of integers `nums` containing `n + 1` integers where each integer is in the range `[1, n]` inclusive, return the duplicate number.

You must solve the problem **without modifying the array** and use only **constant extra space**.

---

## 🔍 Sample Input & Output

**Input:**  
`nums = [3, 1, 3, 4, 2]`  
**Output:**  
`3`

---

## 🚀 Approach

We are using **Floyd's Tortoise and Hare (Cycle Detection)** algorithm to find the duplicate in linear time and constant space.

### Key Idea:

Treat the array like a linked list where each value points to the next index. Due to the duplicate, a cycle will exist, and the entry point of the cycle is the duplicate number.

---

## 🧠 Time & Space Complexity

- **Time Complexity:** `O(n)`
- **Space Complexity:** `O(1)`



✨ What I Learned

How to use cycle detection in arrays

Importance of space optimization

Real-world applications of the Tortoise & Hare algorithm



---

🔗 Part of

This solution is part of my #21DaysOfDSA challenge where I solve one DSA problem each day using JavaScript.

Follow my journey on LinkedIn 🚀

