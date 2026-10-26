# 🔮 Chapter 13: Advanced Data Structures

> **Specialized structures for specialized problems!**

---

## 🎯 Chapter Overview

Advanced data structures solve specific problem types efficiently. These appear in harder interviews and competitive programming.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Advanced |
| **Prerequisites** | Trees, Graphs, Basic DS |
| **Time Estimate** | 2-3 weeks |
| **LeetCode Coverage** | ~60+ problems |

---

## 📁 Module Structure

```
chapter_13_advanced_structures/
├── module_01_trie_advanced/           # Prefix tree applications
├── module_02_segment_tree/            # Range queries, updates
├── module_03_fenwick_tree/            # Binary indexed tree (BIT)
├── module_04_union_find_advanced/     # Path compression, rank
├── module_05_monotonic_structures/    # Monotonic queue/deque
└── module_06_custom_structures/       # Skip list, bloom filter
```

---

## 🧠 Core Structures Covered

### 1️⃣ Trie (Prefix Tree)
```
Use Case: Prefix search, autocomplete, word dictionary
Operations: Insert O(m), Search O(m), StartsWith O(m)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Implement Trie | Medium | 208 |
| Design Add and Search Words | Medium | 211 |
| Word Search II | Hard | 212 |
| Replace Words | Medium | 648 |

### 2️⃣ Segment Tree
```
Use Case: Range queries (sum, min, max) with updates
Operations: Build O(n), Query O(log n), Update O(log n)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Range Sum Query - Mutable | Medium | 307 |
| Count of Smaller Numbers After Self | Hard | 315 |
| My Calendar I, II, III | Medium/Hard | 729, 731, 732 |

### 3️⃣ Fenwick Tree (BIT)
```
Use Case: Prefix sums with point updates
Operations: Update O(log n), Query O(log n)
Simpler than segment tree for sum queries
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Count of Range Sum | Hard | 327 |
| Reverse Pairs | Hard | 493 |

### 4️⃣ Union-Find (Disjoint Set)
```
Use Case: Connectivity, grouping, cycle detection
Operations: Find O(α(n)), Union O(α(n))
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Number of Islands II | Hard | 305 |
| Accounts Merge | Medium | 721 |
| Redundant Connection | Medium | 684 |
| Longest Consecutive Sequence | Medium | 128 |

### 5️⃣ Monotonic Structures
```
Use Case: Next greater, sliding window max/min
Operations: Amortized O(1)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Sliding Window Maximum | Hard | 239 |
| Largest Rectangle in Histogram | Hard | 84 |
| Maximal Rectangle | Hard | 85 |

---

## 💡 Key Templates

### Trie Node
```python
class TrieNode:
    def __init__(self):
        self.children = {}
        self.is_end = False

class Trie:
    def __init__(self):
        self.root = TrieNode()
    
    def insert(self, word):
        node = self.root
        for char in word:
            if char not in node.children:
                node.children[char] = TrieNode()
            node = node.children[char]
        node.is_end = True
```

### Segment Tree
```python
class SegmentTree:
    def __init__(self, nums):
        self.n = len(nums)
        self.tree = [0] * (2 * self.n)
        self.build(nums)
    
    def build(self, nums):
        for i in range(self.n):
            self.tree[self.n + i] = nums[i]
        for i in range(self.n - 1, 0, -1):
            self.tree[i] = self.tree[2*i] + self.tree[2*i + 1]
    
    def update(self, i, val):
        i += self.n
        self.tree[i] = val
        while i > 1:
            i //= 2
            self.tree[i] = self.tree[2*i] + self.tree[2*i + 1]
    
    def query(self, l, r):  # [l, r)
        l += self.n
        r += self.n
        result = 0
        while l < r:
            if l & 1:
                result += self.tree[l]
                l += 1
            if r & 1:
                r -= 1
                result += self.tree[r]
            l //= 2
            r //= 2
        return result
```

---

## ✅ Learning Objectives

- [ ] Implement Trie for prefix operations
- [ ] Build and query segment trees
- [ ] Use Fenwick tree for efficient prefix sums
- [ ] Apply Union-Find with optimizations
- [ ] Recognize when advanced structures are needed

---

**🚀 Start with `module_01_trie_advanced` - it's the most common in interviews!**
