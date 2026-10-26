# 🔄 Chapter 07: Recursion & Backtracking

> **Explore all possibilities systematically!**

---

## 🎯 Chapter Overview

Recursion is the foundation of many algorithms. Backtracking extends recursion to explore choices and undo bad decisions. Essential for combinatorial problems.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate → Advanced |
| **Prerequisites** | Recursion basics, Trees |
| **Time Estimate** | 2 weeks |
| **LeetCode Coverage** | ~100+ problems |

---

## 📁 Module Structure

```
chapter_07_recursion_backtracking/
├── module_01_recursion_fundamentals/  # Thinking recursively, base cases
├── module_02_subsets_combinations/    # Generate all subsets, combinations
├── module_03_permutations/            # Permutations, arrangements
├── module_04_partition_problems/      # Partition, palindrome partition
├── module_05_constraint_search/       # N-Queens, Sudoku, word search
└── module_06_advanced_backtracking/   # Pruning, optimization
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Recursion Fundamentals
```
Key Insight: Trust the recursion!
Define: Base case + Recursive case
Think: "If recursion solves smaller, how to build from that?"
```

### 2️⃣ Subsets & Combinations
```
Keywords: "all subsets", "combinations", "choose k"
Pattern: Include or exclude each element
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Subsets | Medium | 78 |
| Subsets II (duplicates) | Medium | 90 |
| Combinations | Medium | 77 |
| Combination Sum | Medium | 39 |
| Combination Sum II | Medium | 40 |
| Letter Combinations of Phone | Medium | 17 |

### 3️⃣ Permutations
```
Keywords: "all arrangements", "permutations", "order matters"
Pattern: Try each unused element at current position
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Permutations | Medium | 46 |
| Permutations II (duplicates) | Medium | 47 |
| Next Permutation | Medium | 31 |
| Permutation Sequence | Hard | 60 |

### 4️⃣ Partition Problems
```
Keywords: "partition", "split into parts"
Pattern: Try each split point, recurse on remainder
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Palindrome Partitioning | Medium | 131 |
| Restore IP Addresses | Medium | 93 |
| Partition to K Equal Subsets | Medium | 698 |

### 5️⃣ Constraint Satisfaction
```
Keywords: "valid placement", "board", "queens", "sudoku"
Pattern: Place, validate, recurse, backtrack if invalid
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| N-Queens | Hard | 51 |
| N-Queens II | Hard | 52 |
| Sudoku Solver | Hard | 37 |
| Word Search | Medium | 79 |
| Word Search II | Hard | 212 |

---

## 📊 Backtracking Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│              GENERATE ALL POSSIBILITIES?                        │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [SUBSETS?]           [PERMUTATIONS?]     [CONSTRAINT?]
         │                    │                    │
         ▼                    ▼                    ▼
   Include/Exclude      Use/Don't use        Try, validate,
   each element         (swap positions)      backtrack
```

---

## 💡 Key Templates

### Backtracking Template
```python
def backtrack(candidates, path, result, start):
    # Base case: valid solution found
    if is_solution(path):
        result.append(path[:])  # Copy!
        return
    
    for i in range(start, len(candidates)):
        # Pruning (optional)
        if not is_valid(candidates[i]):
            continue
        
        # Choose
        path.append(candidates[i])
        
        # Explore
        backtrack(candidates, path, result, i + 1)  # i or i+1 based on reuse
        
        # Un-choose (backtrack)
        path.pop()

def solve(candidates):
    result = []
    backtrack(candidates, [], result, 0)
    return result
```

### Permutations Template
```python
def permute(nums):
    result = []
    
    def backtrack(start):
        if start == len(nums):
            result.append(nums[:])
            return
        
        for i in range(start, len(nums)):
            nums[start], nums[i] = nums[i], nums[start]  # swap
            backtrack(start + 1)
            nums[start], nums[i] = nums[i], nums[start]  # undo
    
    backtrack(0)
    return result
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Think recursively and trust the recursion
- [ ] Generate all subsets and combinations
- [ ] Generate all permutations
- [ ] Apply backtracking to constraint problems
- [ ] Implement efficient pruning strategies
- [ ] Handle duplicates correctly
- [ ] Solve classic problems: N-Queens, Sudoku

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Backtracking | → DP (Chapter 06) - for optimization |
| Backtracking | → Graphs DFS (Chapter 05) |

---

**🚀 Start with `module_01_recursion_fundamentals` to build the mindset!**
