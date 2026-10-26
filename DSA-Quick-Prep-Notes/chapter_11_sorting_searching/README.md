# 📊 Chapter 11: Sorting & Searching

> **Fundamental algorithms every programmer must know!**

---

## 🎯 Chapter Overview

Sorting and searching are building blocks for countless algorithms. Understanding their implementations and trade-offs is essential.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Beginner → Intermediate |
| **Prerequisites** | Arrays, Recursion |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~60+ problems |

---

## 📁 Module Structure

```
chapter_11_sorting_searching/
├── module_01_sorting_fundamentals/    # Bubble, selection, insertion
├── module_02_efficient_sorts/         # Merge sort, quick sort
├── module_03_non_comparison/          # Counting, radix, bucket sort
├── module_04_search_algorithms/       # Linear, binary, interpolation
└── module_05_sorting_applications/    # Custom comparators, sort problems
```

---

## 🧠 Core Algorithms

### Sorting Comparison
| Algorithm | Time (Avg) | Time (Worst) | Space | Stable |
|-----------|-----------|--------------|-------|--------|
| Bubble | O(n²) | O(n²) | O(1) | ✅ |
| Selection | O(n²) | O(n²) | O(1) | ❌ |
| Insertion | O(n²) | O(n²) | O(1) | ✅ |
| Merge | O(n log n) | O(n log n) | O(n) | ✅ |
| Quick | O(n log n) | O(n²) | O(log n) | ❌ |
| Heap | O(n log n) | O(n log n) | O(1) | ❌ |
| Counting | O(n + k) | O(n + k) | O(k) | ✅ |

### Key Problems
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Sort an Array | Medium | 912 |
| Kth Largest Element | Medium | 215 |
| Sort Colors | Medium | 75 |
| Merge Sorted Array | Easy | 88 |
| Largest Number | Medium | 179 |

---

**🚀 Start with `module_01_sorting_fundamentals` to understand the basics!**
