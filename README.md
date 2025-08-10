Problem link: https://leetcode.com/problems/longest-substring-without-repeating-characters/

Approach
Sliding Window Technique

1.Initialize Pointers

Use two pointers left and right to represent the current substring window.

2.Track Characters

Use a set to store unique characters in the current window.

3.Expand and Shrink Window

Move right pointer to add new characters.

If a duplicate is found, move left pointer until the duplicate is removed.

4.Track Maximum Length

Keep updating the maximum length whenever a longer valid substring is found.

Complexity

Time: O(n) — each character is visited at most twice.

Space: O(min(n, a)) — where a is the size of the character set.

Code

See Solution.py for implementation.
