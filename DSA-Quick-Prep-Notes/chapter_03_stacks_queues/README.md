# 📚 Chapter 03: Stacks & Queues

> **LIFO and FIFO - The gatekeepers of ordered processing!**

---

## 🎯 Chapter Overview

Stacks and Queues are fundamental linear data structures. They're essential for expression evaluation, backtracking, BFS, and many classic interview problems.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Beginner → Intermediate |
| **Prerequisites** | Arrays, Linked Lists basics |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~100+ problems |

---

## 📁 Module Structure

```
chapter_03_stacks_queues/
├── module_01_stack_fundamentals/      # Stack operations, implementation
├── module_02_monotonic_stack/         # Next greater, temperatures
├── module_03_expression_eval/         # Calculator, RPN, parsing
├── module_04_queue_fundamentals/      # Queue, deque, circular queue
└── module_05_advanced_patterns/       # Min stack, queue with stacks
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Stack Fundamentals
```
Keywords: "LIFO", "undo", "nested", "matching"
Core: push, pop, peek, isEmpty
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Valid Parentheses | Easy | 20 |
| Min Stack | Medium | 155 |
| Implement Stack using Queues | Easy | 225 |
| Baseball Game | Easy | 682 |

### 2️⃣ Monotonic Stack Pattern
```
Keywords: "next greater", "next smaller", "temperatures", "histogram"
Complexity: O(n) - each element pushed/popped once
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Next Greater Element I | Easy | 496 |
| Next Greater Element II | Medium | 503 |
| Daily Temperatures | Medium | 739 |
| Largest Rectangle in Histogram | Hard | 84 |
| Trapping Rain Water | Hard | 42 |

### 3️⃣ Expression Evaluation
```
Keywords: "calculator", "evaluate", "parse", "RPN"
Skills: Operator precedence, postfix notation
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Basic Calculator | Hard | 224 |
| Basic Calculator II | Medium | 227 |
| Evaluate RPN | Medium | 150 |
| Decode String | Medium | 394 |

### 4️⃣ Queue Patterns
```
Keywords: "FIFO", "level order", "sliding window max"
Core: enqueue, dequeue, front, back
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Implement Queue using Stacks | Easy | 232 |
| Design Circular Queue | Medium | 622 |
| Sliding Window Maximum | Hard | 239 |
| Number of Recent Calls | Easy | 933 |

### 5️⃣ Advanced Stack/Queue
```
Keywords: "min in O(1)", "max queue", "design"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Max Stack | Hard | 716 |
| Design Browser History | Medium | 1472 |
| Online Stock Span | Medium | 901 |
| Remove K Digits | Medium | 402 |

---

## 📊 Stack/Queue Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                  PROCESSING ORDER MATTERS?                      │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [NESTED/MATCHING?]   [NEXT GREATER?]      [LEVEL BY LEVEL?]
         │                    │                    │
         ▼                    ▼                    ▼
      Stack              Monotonic               Queue
    (parentheses)          Stack               (BFS-like)
```

---

## 💡 Key Templates

### Monotonic Decreasing Stack
```python
# Find next greater element for each position
stack = []  # stores indices
result = [-1] * len(nums)

for i, num in enumerate(nums):
    while stack and nums[stack[-1]] < num:
        result[stack.pop()] = num
    stack.append(i)
```

### Evaluate Expression with Stack
```python
stack = []
num = 0
sign = 1

for char in expression:
    if char.isdigit():
        num = num * 10 + int(char)
    elif char in '+-':
        stack.append(sign * num)
        num = 0
        sign = 1 if char == '+' else -1
    elif char == '(':
        stack.append(sign)
        stack.append('(')
        sign = 1
    elif char == ')':
        stack.append(sign * num)
        num = 0
        # Pop until '('
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Implement stack and queue from scratch
- [ ] Use stacks for parentheses matching and validation
- [ ] Apply monotonic stack for "next greater" problems
- [ ] Evaluate mathematical expressions with proper precedence
- [ ] Implement queue using stacks and vice versa
- [ ] Solve sliding window maximum with deque
- [ ] Design data structures with O(1) min/max operations

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Stacks | → Trees DFS (Chapter 04) |
| Queues | → Trees BFS (Chapter 04) |
| Queues | → Graph BFS (Chapter 06) |

---

**🚀 Start with `module_01_stack_fundamentals` to build your foundation!**
