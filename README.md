# Array-Reduced-Transformation-LeetCode-
**LeetCode Solution - [Array Reduce Transformation]**

This repository contains my solution to the LeetCode problem titled Array reduce transformation.
https://leetcode.com/problems/array-reduce-transformation

**Problem Description**

Given an integer array nums, a reducer function fn, and an initial value init, return a reduced array.

A reduced array is created by applying the following operation: val = fn(init, nums[0]), val = fn(val, nums[1]), val = fn(val, nums[2]), ... until every element in the array has been processed. The final value of val is returned.

If the length of the array is 0, it should return init.

**Code Explanation**

The reduce function takes an array of numbers nums, a callback function fn, and an initial value init. It iterates over each element in the array and applies the callback function to the current element and the accumulated value. The updated value becomes the new accumulated value. Finally, the function returns the accumulated value. This custom implementation allows for reducing an array into a single value based on a specified operation defined by the callback function.
