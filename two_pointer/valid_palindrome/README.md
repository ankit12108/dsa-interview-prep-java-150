# 🧩 Valid Palindrome — Two Pointer Technique

## 🔍 Problem
Given a string `s`, determine whether it is a **palindrome**, considering **only alphanumeric characters** and **ignoring cases**.

Example:  
Input: s = "Was it a car or a cat I saw?"

Output: true

---

## 💡 Approach — Two Pointer
Use two pointers:
- `left` → start of the string
- `right` → end of the string

Steps:
1. Skip characters that are **not alphanumeric**
2. Compare characters at `left` and `right` after converting to lowercase
3. If mismatch → return `false`
4. If all valid chars match while pointers move inward → return `true`

---

## ⏱ Time & Space Complexity
| Complexity | Value |
|-----------|-------|
| Time | **O(n)** — single pass over the string |
| Space | **O(1)** — no extra data structure used |

---



