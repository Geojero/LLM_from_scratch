# 💰 Chapter 08: Greedy Algorithms

> **Make the locally optimal choice at each step!**

---

## 🎯 Chapter Overview

Greedy algorithms make the best choice at each step, hoping to find the global optimum. They're elegant but require proving correctness.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate |
| **Prerequisites** | Sorting, Basic math |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~80+ problems |

---

## 📁 Module Structure

```
chapter_08_greedy/
├── module_01_greedy_fundamentals/     # When greedy works, proof techniques
├── module_02_interval_problems/       # Meeting rooms, merge intervals
├── module_03_array_greedy/            # Jump game, gas station
├── module_04_scheduling/              # Task scheduling, deadlines
└── module_05_string_greedy/           # Remove K digits, reorganize string
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Interval Scheduling
```
Keywords: "meetings", "intervals", "non-overlapping"
Strategy: Sort by end time, greedily pick earliest finishing
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Merge Intervals | Medium | 56 |
| Non-overlapping Intervals | Medium | 435 |
| Meeting Rooms | Easy | 252 |
| Meeting Rooms II | Medium | 253 |
| Insert Interval | Medium | 57 |

### 2️⃣ Array/Sequence Greedy
```
Keywords: "jump", "reach", "gas", "maximum"
Strategy: Maintain running best/reachable
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Jump Game | Medium | 55 |
| Jump Game II | Medium | 45 |
| Gas Station | Medium | 134 |
| Candy | Hard | 135 |
| Best Time to Buy and Sell Stock II | Medium | 122 |

### 3️⃣ String/Digit Greedy
```
Keywords: "remove", "smallest", "lexicographic"
Strategy: Use stack, remove larger when smaller comes
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Remove K Digits | Medium | 402 |
| Remove Duplicate Letters | Medium | 316 |
| Reorganize String | Medium | 767 |
| Task Scheduler | Medium | 621 |

---

## 💡 Key Templates

### Interval Greedy Template
```python
def eraseOverlapIntervals(intervals):
    intervals.sort(key=lambda x: x[1])  # Sort by end time!
    
    count = 0
    prev_end = float('-inf')
    
    for start, end in intervals:
        if start >= prev_end:
            prev_end = end  # Take this interval
        else:
            count += 1  # Skip (overlap)
    
    return count
```

---

## ✅ Learning Objectives

- [ ] Recognize when greedy works
- [ ] Apply interval scheduling greedy
- [ ] Solve jump/reachability problems
- [ ] Use greedy for string optimization

---

**🚀 Start with `module_01_greedy_fundamentals` to understand when greedy applies!**
