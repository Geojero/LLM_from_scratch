# 🌳 Chapter 04: Trees

> **Hierarchical data mastery - From binary trees to tries!**

---

## 🎯 Chapter Overview

Trees are hierarchical structures that appear everywhere: file systems, DOM, organization charts. This chapter covers all tree patterns from basic traversals to advanced structures.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate → Advanced |
| **Prerequisites** | Recursion, Stacks, Queues |
| **Time Estimate** | 2-3 weeks |
| **LeetCode Coverage** | ~150+ problems |

---

## 📁 Module Structure

```
chapter_04_trees/
├── module_01_tree_fundamentals/       # Tree concepts, node creation
├── module_02_tree_traversals/         # DFS (pre/in/post), BFS
├── module_03_bst_operations/          # Search, insert, delete, validate
├── module_04_tree_construction/       # Build from traversals
├── module_05_tree_path_problems/      # Path sum, LCA, diameter
├── module_06_tree_views/              # Right view, boundary, vertical
└── module_07_trie/                    # Prefix tree, autocomplete
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Tree Traversals
```
DFS: Preorder (root-left-right), Inorder (left-root-right), Postorder (left-right-root)
BFS: Level order (queue-based)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Binary Tree Inorder Traversal | Easy | 94 |
| Binary Tree Level Order Traversal | Medium | 102 |
| Binary Tree Zigzag Level Order | Medium | 103 |
| N-ary Tree Level Order | Medium | 429 |

### 2️⃣ Binary Search Tree (BST)
```
Keywords: "sorted order", "successor", "kth smallest"
Property: left < root < right
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Validate BST | Medium | 98 |
| Search in BST | Easy | 700 |
| Insert into BST | Medium | 701 |
| Delete Node in BST | Medium | 450 |
| Kth Smallest Element in BST | Medium | 230 |

### 3️⃣ Tree Construction
```
Keywords: "construct", "build from", "serialize"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Construct BT from Preorder/Inorder | Medium | 105 |
| Construct BT from Inorder/Postorder | Medium | 106 |
| Serialize and Deserialize BT | Hard | 297 |
| Maximum Binary Tree | Medium | 654 |

### 4️⃣ Path Problems
```
Keywords: "path sum", "root to leaf", "diameter", "LCA"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Path Sum | Easy | 112 |
| Path Sum II | Medium | 113 |
| Binary Tree Maximum Path Sum | Hard | 124 |
| Diameter of Binary Tree | Easy | 543 |
| Lowest Common Ancestor | Medium | 236 |

### 5️⃣ Tree Properties
```
Keywords: "height", "balanced", "symmetric", "same tree"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Maximum Depth of Binary Tree | Easy | 104 |
| Balanced Binary Tree | Easy | 110 |
| Symmetric Tree | Easy | 101 |
| Same Tree | Easy | 100 |
| Invert Binary Tree | Easy | 226 |

### 6️⃣ Trie (Prefix Tree)
```
Keywords: "prefix", "autocomplete", "word search", "dictionary"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Implement Trie | Medium | 208 |
| Design Add and Search Words | Medium | 211 |
| Word Search II | Hard | 212 |
| Replace Words | Medium | 648 |

---

## 📊 Tree Problem Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                      TREE PROBLEM?                              │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [TRAVERSAL?]         [BST PROPERTY?]      [PATH/DEPTH?]
         │                    │                    │
    ┌────┴────┐              │                    │
    ▼         ▼              ▼                    ▼
   DFS       BFS         Inorder is          Recursion
 (Stack)   (Queue)        sorted!           return value
```

---

## 💡 Key Templates

### Recursive DFS Template
```python
def dfs(node):
    if not node:
        return base_case
    
    left_result = dfs(node.left)
    right_result = dfs(node.right)
    
    return combine(node.val, left_result, right_result)
```

### Level Order BFS Template
```python
from collections import deque

def bfs(root):
    if not root:
        return []
    
    queue = deque([root])
    result = []
    
    while queue:
        level_size = len(queue)
        level = []
        
        for _ in range(level_size):
            node = queue.popleft()
            level.append(node.val)
            
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)
        
        result.append(level)
    
    return result
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Implement all tree traversals (iterative and recursive)
- [ ] Understand BST properties and operations
- [ ] Construct trees from traversal sequences
- [ ] Solve path-based tree problems
- [ ] Calculate tree properties (depth, diameter, balance)
- [ ] Implement and use Trie for prefix operations
- [ ] Choose between DFS and BFS based on problem type

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Trees | → Graphs (Chapter 05) |
| Trees | → Heap (Chapter 01 - Module 06) |
| Trie | → String patterns (Chapter 01) |

---

**🚀 Start with `module_01_tree_fundamentals` to understand the structure!**
