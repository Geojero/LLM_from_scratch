# 📚 Chapter 01: Arrays & Array Patterns

> **The foundation of all DSA - Master arrays, master everything!**

---

## 🎯 Chapter Overview

Arrays are the most fundamental data structure. This chapter covers **all core array patterns** that appear in 60%+ of LeetCode problems.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Beginner → Intermediate |
| **Prerequisites** | Python basics (variables, loops, functions) |
| **Time Estimate** | 2-3 weeks |
| **LeetCode Coverage** | ~200+ problems |

---

## 📁 Module Structure

```
chapter_01_arrays/
├── module_00_python_prerequisites/    # Python refresher for DSA
├── module_01_fundamentals/            # Big O, problem-solving mindset
├── module_02_two_pointer/             # Two pointer technique
├── module_03_prefix_sum/              # Prefix sum pattern
├── module_04_binary_search/           # Binary search variations
├── module_05_subarray_patterns/       # Kadane's & subarray problems
├── module_06_heap_topk/               # Heap & Top K problems
├── module_07_sliding_window/          # Fixed & variable window
└── module_08_string_patterns/         # String manipulation patterns
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Two Pointer Pattern
```
Keywords: "sorted array", "pairs", "triplets", "palindrome"
Complexity: O(n) or O(n²) for multi-pointer
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Two Sum II | Easy | 167 |
| 3Sum | Medium | 15 |
| Container With Most Water | Medium | 11 |
| Trapping Rain Water | Hard | 42 |

### 2️⃣ Prefix Sum Pattern
```
Keywords: "range sum", "subarray sum", "cumulative"
Complexity: O(n) preprocessing, O(1) query
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Range Sum Query | Easy | 303 |
| Subarray Sum Equals K | Medium | 560 |
| Product of Array Except Self | Medium | 238 |

### 3️⃣ Binary Search Pattern
```
Keywords: "sorted", "minimum/maximum", "search", "rotated"
Complexity: O(log n)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Binary Search | Easy | 704 |
| Search in Rotated Array | Medium | 33 |
| Find Minimum in Rotated | Medium | 153 |
| Koko Eating Bananas | Medium | 875 |

### 4️⃣ Sliding Window Pattern
```
Keywords: "substring", "contiguous", "at most K", "longest/shortest"
Complexity: O(n)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Longest Substring Without Repeating | Medium | 3 |
| Minimum Window Substring | Hard | 76 |
| Permutation in String | Medium | 567 |

### 5️⃣ Kadane's Algorithm
```
Keywords: "maximum subarray", "contiguous sum"
Complexity: O(n)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Maximum Subarray | Medium | 53 |
| Maximum Product Subarray | Medium | 152 |
| Best Time to Buy and Sell Stock | Easy | 121 |

### 6️⃣ Heap / Top K Pattern
```
Keywords: "K largest", "K smallest", "Kth element"
Complexity: O(n log k)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Kth Largest Element | Medium | 215 |
| Top K Frequent Elements | Medium | 347 |
| K Closest Points to Origin | Medium | 973 |

---

## 📊 Problem-Solving Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                    ARRAY PROBLEM?                               │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [SORTED?]            [SUBARRAY?]          [K ELEMENTS?]
         │                    │                    │
    ┌────┴────┐          ┌────┴────┐              │
    ▼         ▼          ▼         ▼              ▼
 Binary    Two      Sliding    Prefix           Heap
 Search   Pointer   Window      Sum           (Top K)
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Understand Big O notation and analyze algorithm complexity
- [ ] Master the two-pointer technique for sorted arrays
- [ ] Apply prefix sum for range query problems
- [ ] Implement binary search and its variations
- [ ] Use sliding window for substring/subarray problems
- [ ] Apply Kadane's algorithm for maximum subarray
- [ ] Utilize heaps for Top K problems
- [ ] Recognize which pattern to apply based on problem keywords

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Arrays | → Linked Lists (Chapter 02) |
| Arrays | → Stacks & Queues (Chapter 03) |
| Binary Search | → Binary Search Trees (Chapter 04) |

---

## 🎯 Mastery Checklist

Complete each module's checkpoint before moving on:

- [ ] Module 00: Python Prerequisites Checkpoint
- [ ] Module 01: Fundamentals Checkpoint  
- [ ] Module 02: Two Pointer Checkpoint
- [ ] Module 03: Prefix Sum Checkpoint
- [ ] Module 04: Binary Search Checkpoint
- [ ] Module 05: Subarray Patterns Checkpoint
- [ ] Module 06: Heap/TopK Checkpoint
- [ ] Module 07: Sliding Window Checkpoint
- [ ] Module 08: String Patterns Checkpoint

---

**🚀 Start with `module_00_python_prerequisites` if new to Python, otherwise begin with `module_01_fundamentals`!**
