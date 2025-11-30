# 01 — Two Sum (Sorted)
🔹 Difficulty: Medium  
🔹 Category: Two Pointer

## 💡 Approach
Use two pointers — left at start, right at end → shrink depending on sum.
- if you are getting sum is bigger then move right pointer
- if you are getting sum is low then move left to right
  
## for visualization
<img width="1405" height="420" alt="image" src="https://github.com/user-attachments/assets/33a29eac-52b6-4064-bc1f-2a651ae544c0" />


## ⏱ Time Complexity
O(n)

## 🧪 Example
Input: [2,7,11,15], target = 9  
Output: [1,2]

=======
# 01 — Two Sum (Sorted)
🔹 Difficulty: Medium  
🔹 Category: Two Pointer

## 💡 Approach
Use two pointers — one at the start (left) and one at the end (right) — and adjust them based on the current sum:
- If the current sum is greater than the target, move the right pointer left (to reduce the sum)
- If the current sum is less than the target, move the left pointer right (to increase the sum)
  
## for visualization
<img width="1405" height="420" alt="image" src="https://github.com/user-attachments/assets/33a29eac-52b6-4064-bc1f-2a651ae544c0" />


## ⏱ Time Complexity
O(n)

## 🧪 Example
Input: [2,7,11,15], target = 9  
Output: [1,2]


>>>>>>> 181595e27014eeaf8d105a3a0f0907306ca6dd21:two_pointer/README.md
