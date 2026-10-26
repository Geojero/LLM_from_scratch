# 📝 Chapter 02: Strings

> **Master text manipulation and pattern matching!**

---

## 🎯 Chapter Overview

String problems are everywhere in interviews. This chapter covers string-specific patterns beyond array techniques, including KMP, Z-algorithm, and advanced manipulation.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Beginner → Intermediate |
| **Prerequisites** | Arrays, Hash Maps |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~100+ problems |

---

## 📁 Module Structure

```
chapter_02_strings/
├── module_01_string_fundamentals/     # Python strings, common operations
├── module_02_string_matching/         # KMP, Rabin-Karp, Z-algorithm
├── module_03_anagram_palindrome/      # Anagram, palindrome patterns
├── module_04_string_building/         # StringBuilder, manipulation
└── module_05_advanced_strings/        # Parsing, encoding, compression
```

---

## 🧠 Core Patterns Covered

### 1️⃣ String Basics
```
Keywords: "reverse", "substring", "compare"
Python: immutable, use list for in-place
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Reverse String | Easy | 344 |
| Reverse Words in a String | Medium | 151 |
| Valid Palindrome | Easy | 125 |
| String to Integer (atoi) | Medium | 8 |

### 2️⃣ Pattern Matching
```
Keywords: "find pattern", "match", "repeated"
Algorithms: KMP O(n+m), Rabin-Karp O(n)
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Implement strStr() | Medium | 28 |
| Repeated Substring Pattern | Easy | 459 |
| Shortest Palindrome | Hard | 214 |

### 3️⃣ Anagram & Palindrome
```
Keywords: "anagram", "palindrome", "rearrange"
Technique: Character counting, two pointer
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Valid Anagram | Easy | 242 |
| Group Anagrams | Medium | 49 |
| Longest Palindrome | Easy | 409 |
| Longest Palindromic Substring | Medium | 5 |
| Palindrome Partitioning | Medium | 131 |

### 4️⃣ String Building
```
Keywords: "build", "construct", "modify"
Technique: List append then join
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Add Binary | Easy | 67 |
| Multiply Strings | Medium | 43 |
| Integer to Roman | Medium | 12 |
| Roman to Integer | Easy | 13 |
| ZigZag Conversion | Medium | 6 |

### 5️⃣ Encoding & Parsing
```
Keywords: "decode", "encode", "compress"
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Decode String | Medium | 394 |
| String Compression | Medium | 443 |
| Count and Say | Medium | 38 |
| Encode and Decode Strings | Medium | 271 |

---

## 📊 String Problem Decision Tree

```
┌─────────────────────────────────────────────────────────────────┐
│                      STRING PROBLEM?                            │
└─────────────────────────────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
    [SUBSTRING?]         [ANAGRAM?]           [PATTERN?]
         │                    │                    │
         ▼                    ▼                    ▼
    Sliding           Character               KMP or
    Window             Count                Hash-based
```

---

## 💡 Key Techniques

### String Immutability in Python
```python
# WRONG: strings are immutable
# s[0] = 'A'  # Error!

# RIGHT: convert to list
s_list = list(s)
s_list[0] = 'A'
s = ''.join(s_list)
```

### KMP Algorithm Template
```python
def compute_lps(pattern):
    lps = [0] * len(pattern)
    length = 0
    i = 1
    while i < len(pattern):
        if pattern[i] == pattern[length]:
            length += 1
            lps[i] = length
            i += 1
        elif length != 0:
            length = lps[length - 1]
        else:
            lps[i] = 0
            i += 1
    return lps
```

---

## ✅ Learning Objectives

- [ ] Handle string immutability efficiently
- [ ] Apply pattern matching algorithms
- [ ] Solve anagram and palindrome problems
- [ ] Parse and decode complex strings
- [ ] Use sliding window for substring problems

---

**🚀 Start with `module_01_string_fundamentals` for Python string mastery!**
