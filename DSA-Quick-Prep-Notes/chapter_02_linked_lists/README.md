# 🔗 Chapter 02: Linked Lists

> **Master the art of pointers and node manipulation!**

---

## 🎯 Chapter Overview

Linked Lists are the gateway to pointer-based data structures. They teach you how to think about **references** and **memory**, essential for trees, graphs, and more.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Beginner → Intermediate |
| **Prerequisites** | Arrays, Python classes basics |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~80+ problems |

---

## 📁 Module Structure

```
chapter_02_linked_lists/
├── module_01_ll_fundamentals/         # Node creation, traversal, basics
├── module_02_ll_two_pointer/          # Fast/slow pointer, cycle detection
├── module_03_ll_reversal/             # Reverse techniques
├── module_04_ll_merge_sort/           # Merge, sort, partition
└── module_05_ll_advanced/             # LRU Cache, copy with random pointer
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Linked List Basics
```
Keywords: "create", "traverse", "insert", "delete"
Core Skills: Node class, pointer manipulation
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Design Linked List | Medium | 707 |
| Delete Node in Linked List | Medium | 237 |
| Remove Linked List Elements | Easy | 203 |

### 2️⃣ Fast & Slow Pointer (Floyd's)
```
Keywords: "cycle", "middle", "nth from end"
Complexity: O(n) time, O(1) space
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Linked List Cycle | Easy | 141 |
| Linked List Cycle II | Medium | 142 |
| Middle of Linked List | Easy | 876 |
| Remove Nth Node From End | Medium | 19 |
| Happy Number | Easy | 202 |

### 3️⃣ Reversal Pattern
```
Keywords: "reverse", "swap", "rotate"
Complexity: O(n) time, O(1) space
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Reverse Linked List | Easy | 206 |
| Reverse Linked List II | Medium | 92 |
| Swap Nodes in Pairs | Medium | 24 |
| Reverse Nodes in k-Group | Hard | 25 |
| Palindrome Linked List | Easy | 234 |

### 4️⃣ Merge & Sort Pattern
```
Keywords: "merge", "sort", "intersection"
Complexity: O(n) or O(n log n) for sort
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Merge Two Sorted Lists | Easy | 21 |
| Merge K Sorted Lists | Hard | 23 |
| Sort List | Medium | 148 |
| Intersection of Two Lists | Easy | 160 |

### 5️⃣ Advanced Patterns
```
Keywords: "copy", "flatten", "LRU", "random"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Copy List with Random Pointer | Medium | 138 |
| Flatten Multilevel Doubly LL | Medium | 430 |
| LRU Cache | Medium | 146 |
| Add Two Numbers | Medium | 2 |

---

## 📊 Linked List Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                  LINKED LIST PROBLEM?                           │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [CYCLE/MIDDLE?]      [REVERSE?]           [MERGE?]
         │                    │                    │
         ▼                    ▼                    ▼
    Fast/Slow           Iterative or         Two pointer
    Pointer             Recursive            merge
    
         └────────────────────┴────────────────────┘
                              │
                      [Use dummy head for edge cases!]
```

---

## 💡 Key Techniques

### The Dummy Head Trick
```python
dummy = ListNode(0)
dummy.next = head
# ... manipulate list
return dummy.next
```
**Why?** Simplifies edge cases when head might change.

### Fast/Slow Pointer Template
```python
slow = fast = head
while fast and fast.next:
    slow = slow.next
    fast = fast.next.next
# slow is now at middle (or cycle entry point)
```

### Iterative Reversal Template
```python
prev = None
curr = head
while curr:
    next_temp = curr.next
    curr.next = prev
    prev = curr
    curr = next_temp
return prev  # new head
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Understand how pointers/references work in Python
- [ ] Create and manipulate linked list nodes
- [ ] Apply fast/slow pointer for cycle detection
- [ ] Reverse linked lists iteratively and recursively
- [ ] Merge and sort linked lists
- [ ] Handle edge cases with dummy nodes
- [ ] Implement LRU Cache using linked list + hash map

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Linked Lists | → Stacks & Queues (Chapter 03) |
| Linked Lists | → Trees (Chapter 04) |
| Fast/Slow Pointer | → Graph Cycle Detection (Chapter 06) |

---

**🚀 Start with `module_01_ll_fundamentals` to build your foundation!**
