# 🔢 Chapter 09: Bit Manipulation

> **Master the binary representation for blazing fast operations!**

---

## 🎯 Chapter Overview

Bit manipulation allows O(1) operations that would otherwise be O(n). Essential for optimization and a common interview topic.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate |
| **Prerequisites** | Binary number system |
| **Time Estimate** | 1 week |
| **LeetCode Coverage** | ~50+ problems |

---

## 📁 Module Structure

```
chapter_09_bit_manipulation/
├── module_01_bit_fundamentals/        # AND, OR, XOR, shifts, masks
├── module_02_single_number/           # XOR tricks, finding unique
├── module_03_counting_bits/           # Count set bits, power of 2
└── module_04_advanced_bits/           # Bitwise DP, subset with bits
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Bit Operations
```
AND (&): Both 1 → 1
OR (|):  Either 1 → 1
XOR (^): Different → 1 (same → 0)
NOT (~): Flip all bits
<< : Left shift (multiply by 2)
>> : Right shift (divide by 2)
```

### 2️⃣ Key Problems
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Single Number | Easy | 136 |
| Single Number II | Medium | 137 |
| Single Number III | Medium | 260 |
| Number of 1 Bits | Easy | 191 |
| Counting Bits | Easy | 338 |
| Power of Two | Easy | 231 |
| Reverse Bits | Easy | 190 |
| Missing Number | Easy | 268 |

---

## 💡 Key Tricks

```python
# Check if power of 2
n & (n - 1) == 0

# Get rightmost set bit
n & (-n)

# Toggle bit at position i
n ^ (1 << i)

# Find missing number (XOR all)
result = 0
for i in range(len(nums) + 1):
    result ^= i
for num in nums:
    result ^= num
# result is missing number
```

---

**🚀 Start with `module_01_bit_fundamentals` to understand binary operations!**
