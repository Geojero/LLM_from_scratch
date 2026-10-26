# 🕸️ Chapter 05: Graphs

> **The ultimate data structure for relationships and networks!**

---

## 🎯 Chapter Overview

Graphs model connections: social networks, maps, dependencies, state machines. This chapter covers representation, traversals, and classic graph algorithms.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate → Advanced |
| **Prerequisites** | Trees, BFS/DFS, Hash Maps |
| **Time Estimate** | 2-3 weeks |
| **LeetCode Coverage** | ~120+ problems |

---

## 📁 Module Structure

```
chapter_05_graphs/
├── module_01_graph_fundamentals/      # Representation, terminology
├── module_02_graph_bfs/               # Shortest path, level-based
├── module_03_graph_dfs/               # Connected components, cycles
├── module_04_topological_sort/        # DAG ordering, course schedule
├── module_05_union_find/              # Disjoint sets, connectivity
├── module_06_shortest_path/           # Dijkstra, Bellman-Ford
└── module_07_advanced_graphs/         # MST, network flow basics
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Graph Representation
```
Adjacency List: graph[node] = [neighbors]  (most common)
Adjacency Matrix: graph[i][j] = 1/0
Edge List: [(u, v, weight), ...]
```

### 2️⃣ BFS on Graphs
```
Keywords: "shortest path (unweighted)", "closest", "minimum steps"
Complexity: O(V + E)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Clone Graph | Medium | 133 |
| Word Ladder | Hard | 127 |
| Rotting Oranges | Medium | 994 |
| 01 Matrix | Medium | 542 |
| Shortest Path in Binary Matrix | Medium | 1091 |

### 3️⃣ DFS on Graphs
```
Keywords: "traverse", "connected", "path exists", "cycle"
Complexity: O(V + E)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Number of Islands | Medium | 200 |
| Number of Provinces | Medium | 547 |
| Pacific Atlantic Water Flow | Medium | 417 |
| Course Schedule (cycle detection) | Medium | 207 |
| Surrounded Regions | Medium | 130 |

### 4️⃣ Topological Sort
```
Keywords: "order", "dependencies", "prerequisites", "schedule"
Applies to: DAGs (Directed Acyclic Graphs)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Course Schedule II | Medium | 210 |
| Alien Dictionary | Hard | 269 |
| Minimum Height Trees | Medium | 310 |
| Parallel Courses | Medium | 1136 |

### 5️⃣ Union-Find (Disjoint Set)
```
Keywords: "connected", "group", "redundant", "merge"
Complexity: O(α(n)) ≈ O(1) per operation
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Number of Connected Components | Medium | 323 |
| Redundant Connection | Medium | 684 |
| Accounts Merge | Medium | 721 |
| Graph Valid Tree | Medium | 261 |
| Longest Consecutive Sequence | Medium | 128 |

### 6️⃣ Weighted Shortest Path
```
Dijkstra: Non-negative weights, O((V+E) log V)
Bellman-Ford: Handles negative, O(VE)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Network Delay Time | Medium | 743 |
| Cheapest Flights Within K Stops | Medium | 787 |
| Path with Maximum Probability | Medium | 1514 |

---

## 📊 Graph Problem Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                      GRAPH PROBLEM?                             │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [SHORTEST PATH?]     [CONNECTED?]        [ORDERING?]
         │                    │                    │
    ┌────┴────┐          ┌────┴────┐              │
    ▼         ▼          ▼         ▼              ▼
 Unweight  Weighted     BFS/     Union-      Topological
   BFS     Dijkstra     DFS       Find          Sort
```

---

## 💡 Key Templates

### Graph BFS Template
```python
from collections import deque

def bfs(graph, start):
    visited = {start}
    queue = deque([start])
    
    while queue:
        node = queue.popleft()
        for neighbor in graph[node]:
            if neighbor not in visited:
                visited.add(neighbor)
                queue.append(neighbor)
```

### Union-Find Template
```python
class UnionFind:
    def __init__(self, n):
        self.parent = list(range(n))
        self.rank = [0] * n
    
    def find(self, x):
        if self.parent[x] != x:
            self.parent[x] = self.find(self.parent[x])  # Path compression
        return self.parent[x]
    
    def union(self, x, y):
        px, py = self.find(x), self.find(y)
        if px == py:
            return False
        # Union by rank
        if self.rank[px] < self.rank[py]:
            px, py = py, px
        self.parent[py] = px
        if self.rank[px] == self.rank[py]:
            self.rank[px] += 1
        return True
```

---

## ✅ Learning Objectives

By completing this chapter, you will:

- [ ] Represent graphs as adjacency lists/matrices
- [ ] Apply BFS for shortest path in unweighted graphs
- [ ] Use DFS for connectivity and cycle detection
- [ ] Implement topological sort (Kahn's and DFS)
- [ ] Master Union-Find for connectivity problems
- [ ] Apply Dijkstra for weighted shortest path
- [ ] Recognize when each algorithm applies

---

## 🔗 Related Chapters

| After This | Study Next |
|------------|------------|
| Graphs | → Dynamic Programming (Chapter 06) |
| Graphs | → Backtracking (Chapter 07) |
| BFS/DFS | → Trees (Chapter 04) |

---

**🚀 Start with `module_01_graph_fundamentals` to understand representations!**
