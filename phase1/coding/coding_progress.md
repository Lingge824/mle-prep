# Coding Progress

## Week 1 Day 1

Done:
1. Two Sum
   - Pattern: Hash Map
   - Time: O(n)
   - Space: O(n)

2. Contains Duplicate
   - Pattern: Hash Set
   - Time: O(n)
   - Space: O(n)

Notes:
- dict stores key -> value
- set stores unique seen values

## Week 1 Day 2

Done:
3. Valid Anagram
   - Pattern: Hash Map / Sorting
   - Key idea: compare character frequency
   - Time: O(n) with count map or O(n log n) with sorting

4. Group Anagrams
   - Pattern: Hash Map
   - Key idea: use character frequency tuple as key
   - Time: O(n*k)
   - Space: O(n*k)

Notes:
- key = character frequency
- value = list of strings in the same anagram group
