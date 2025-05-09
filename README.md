# Day10-50-days-coding-challenge
## ✅ Problems Solved

### 1. Bulb Switcher
- **Problem Statement:**  
  There are `n` bulbs, initially off. For each round `i` (1 to `n`), toggle every `i`th bulb. Return the number of bulbs that remain ON after `n` rounds.
- **Example:**  
  - Input: `n = 3` → Output: `1`  
  - Input: `n = 0` → Output: `0`
- **Insight:**  
  A bulb toggles every time its position is divisible by the round number.  
  Only bulbs at **perfect square positions** are toggled an **odd number** of times, hence they remain ON.
- **Final Formula:**  
  `Number of bulbs ON = floor(sqrt(n))`
- **Time Complexity:** `O(1)`  
- **Space Complexity:** `O(1)`

---

### 2. Delete the Middle Node of a Linked List
- **Problem Statement:**  
  Given a singly linked list, delete its middle node (⌊n/2⌋-th index in 0-based indexing).
- **Examples:**  
  - Input: `[1,3,4,7,1,2,6]` → Output: `[1,3,4,1,2,6]`  
  - Input: `[1,2,3,4]` → Output: `[1,2,4]`
- **Approach:**  
  1. Use two pointers (slow & fast).  
  2. When fast reaches the end, slow is at middle.  
  3. Remove the node after `prev(slow)`.
- **Edge Case:**  
  If the list has only 1 node, return `nullptr`.
- **Time Complexity:** `O(n)`  
- **Space Complexity:** `O(1)`

---

## 🔍 Concepts Practiced
- Square numbers & mathematical patterns  
- Perfect square counting via square root  
- Two-pointer technique in linked lists  
- Edge case handling for small lists

## 💻 Tools & Language
- Language: C++  
- IDE: VS Code  
- Version Control: Git & GitHub
