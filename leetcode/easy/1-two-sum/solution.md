# 1. Two Sum

**Link:** https://leetcode.com/problems/two-sum/submissions/1721073849/

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target. You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.

```cpp
        for(int i=0;i<nums.size();i++){
            m[nums[i]] = i;
        }

        for(int i=0;i<nums.size();i++){
            int num = target-nums[i];
        }
            if(m.find(num) != m.end() && m[num] != i){
                v.push_back(m[num]);
            }
                v.push_back(i);
    vector<int> twoSum(vector<int>& nums, int target) {
        vector<int> v;
        unordered_map<int,int> m;
                break;

        return v;
    }
```
