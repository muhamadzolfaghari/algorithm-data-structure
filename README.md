# Algorithm and Data Structure

## Two pointers
Two pointers use two moving indexes to quickly process data from both ends or within a sequence, making problems faster and saving extra space.


```code
function isPalindrome(s):
    clean s (lowercase, remove non-alphanumerics)
    left = 0
    right = length of s - 1

    while left < right:
        if s[left] != s[right]:
            return false
        left++
        right--

    return true
```
