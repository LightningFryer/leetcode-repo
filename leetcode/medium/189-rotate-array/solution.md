# 189. Rotate Array

**Link:** https://leetcode.com/problems/rotate-array/submissions/1693056005/

Given an integer array nums, rotate the array to the right by k steps, where k is non-negative.

```java
class Solution {
    public void rotate(int[] nums, int k) {
         int[] numsCopy = nums.clone();

        for (int i = 0; i < nums.length; i++){
            nums[(i + k) % nums.length] = numsCopy[i];
        }
    }
}
```
