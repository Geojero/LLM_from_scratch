# 🧩 Chapter 06: Dynamic Programming

> **The art of solving complex problems by breaking them down!**

---

## 🎯 Chapter Overview

Dynamic Programming (DP) is the most challenging yet rewarding topic. It transforms exponential problems into polynomial time by recognizing and storing overlapping subproblems.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate → Advanced |
| **Prerequisites** | Recursion, Arrays, Strings |
| **Time Estimate** | 3-4 weeks |
| **LeetCode Coverage** | ~200+ problems |

---

## 📁 Module Structure

```
chapter_06_dynamic_programming/
├── module_01_dp_fundamentals/         # Memoization vs tabulation
├── module_02_1d_dp/                   # Climbing stairs, house robber
├── module_03_2d_dp/                   # Grid paths, matrix chain
├── module_04_string_dp/               # LCS, edit distance, palindrome
├── module_05_knapsack/                # 0/1, unbounded, subset sum
├── module_06_interval_dp/             # Burst balloons, stone game
└── module_07_dp_on_trees/             # Tree DP, house robber III
```

---

## 🧠 Core Patterns Covered

### 1️⃣ DP Fundamentals
```
Top-Down (Memoization): Recursive + cache
Bottom-Up (Tabulation): Iterative, build table
State Transition: dp[i] = f(dp[i-1], dp[i-2], ...)
```

### 2️⃣ 1D DP Problems
```
Keywords: "minimum/maximum", "count ways", "can reach"
Pattern: dp[i] depends on previous states
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Climbing Stairs | Easy | 70 |
| House Robber | Medium | 198 |
| House Robber II | Medium | 213 |
| Decode Ways | Medium | 91 |
| Jump Game | Medium | 55 |
| Coin Change | Medium | 322 |

### 3️⃣ 2D DP / Grid Problems
```
Keywords: "grid", "paths", "minimum cost"
Pattern: dp[i][j] depends on dp[i-1][j], dp[i][j-1]
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Unique Paths | Medium | 62 |
| Unique Paths II | Medium | 63 |
| Minimum Path Sum | Medium | 64 |
| Maximal Square | Medium | 221 |
| Dungeon Game | Hard | 174 |

### 4️⃣ String DP
```
Keywords: "subsequence", "substring", "edit", "palindrome"
Pattern: dp[i][j] for s1[0:i] and s2[0:j]
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Longest Common Subsequence | Medium | 1143 |
| Edit Distance | Hard | 72 |
| Longest Palindromic Subsequence | Medium | 516 |
| Longest Palindromic Substring | Medium | 5 |
| Word Break | Medium | 139 |

### 5️⃣ Knapsack Patterns
```
0/1 Knapsack: Each item used at most once
Unbounded: Items can be reused
Subset Sum: Can we achieve target?
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Partition Equal Subset Sum | Medium | 416 |
| Target Sum | Medium | 494 |
| Coin Change 2 | Medium | 518 |
| Ones and Zeroes | Medium | 474 |
| Perfect Squares | Medium | 279 |

### 6️⃣ Interval/Range DP
```
Keywords: "burst", "merge", "game", "cost to remove"
Pattern: dp[i][j] for range [i, j], try all split points
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Burst Balloons | Hard | 312 |
| Minimum Cost Tree From Leaf | Medium | 1130 |
| Stone Game | Medium | 877 |
| Predict the Winner | Medium | 486 |

---

## 📊 DP Problem Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│            CAN BE BROKEN INTO SUBPROBLEMS?                      │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [SEQUENCE?]          [TWO SEQUENCES?]      [KNAPSACK?]
         │                    │                    │
         ▼                    ▼                    ▼
     1D DP              String DP              Subset DP
   (linear)          (2D: i in s1,           (include or
                       j in s2)               exclude)
```

---

## 💡 Key Templates

### 1D DP Template (Fibonacci-style)
```python
def solve(n):
    if n <= 1:
        return base_cases[n]
    
    dp = [0] * (n + 1)
    dp[0], dp[1] = base_cases
    
    for i in range(2, n + 1):
        dp[i] = dp[i-1] + dp[i-2]  # or any recurrence
    
    return dp[n]
```

### 2D String DP Template
```python
def solve(s1, s2):
    m, n = len(s1), len(s2)
    dp = [[0] * (n + 1) for _ in range(m + 1)]
    
    # Base cases
    for i in range(m + 1):
        dp[i][0] = base_i
    for j in range(n + 1):
        dp[0][j] = base_j
    
    for i in range(1, m + 1):
        for j in range(1, n + 1):
            if s1[i-1] == s2[j-1]:
                dp[i][j] = dp[i-1][j-1] + 1
            else:
                dp[i][j] = max(dp[i-1][j], dp[i][j-1])
    
    return dp[m][n]
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Identify when a problem can use DP
- [ ] Choose between top-down and bottom-up approaches
- [ ] Solve 1D DP problems (sequences)
- [ ] Apply 2D DP for grid and string problems
- [ ] Master knapsack variations
- [ ] Handle interval DP problems
- [ ] Optimize space from O(n²) to O(n) when possible

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| DP | → Backtracking (Chapter 07) |
| String DP | → Strings (Chapter 01) |

---

**🚀 Start with `module_01_dp_fundamentals` - understanding the mindset is critical!**
