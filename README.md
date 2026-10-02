# Valid Parentheses

An efficient solution for LeetCode problem (Easy difficulty) implemented in **C++**.

## Problem Description
Given a string `s` containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['` and `']'`, determine if the input string is valid. An input string is valid if:
1. Open brackets must be closed by the same type of brackets.
2. Open brackets must be closed in the correct order.
3. Every close bracket has a corresponding open bracket of the same type.

## Approach & Complexity
- **Algorithm:** Stack (Last-In, First-Out data structure). When an opening bracket is encountered, it is pushed onto the stack. When a closing bracket is encountered, the stack is checked for a matching opening bracket.
- **Time Complexity:** O(N), where N is the length of the string, since we traverse the string once.
- **Space Complexity:** O(N), for storing characters in the stack in the worst-case scenario.

## Code File
- `solution.cpp` — clean stack-based implementation.
