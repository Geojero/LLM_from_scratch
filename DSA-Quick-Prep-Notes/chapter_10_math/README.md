# 🔢 Chapter 10: Math & Number Theory

> **Mathematical foundations for algorithmic problem solving!**

---

## 🎯 Chapter Overview

Math problems test logical thinking and pattern recognition. This chapter covers essential mathematical concepts for coding interviews.

| Aspect | Details |
|--------|---------|
| **Difficulty** | Intermediate |
| **Prerequisites** | Basic math |
| **Time Estimate** | 1-2 weeks |
| **LeetCode Coverage** | ~70+ problems |

---

## 📁 Module Structure

```
chapter_10_math/
├── module_01_math_fundamentals/       # GCD, LCM, modular arithmetic
├── module_02_primes_factors/          # Prime check, sieve, factorization
├── module_03_number_properties/       # Palindrome, digit manipulation
├── module_04_combinatorics/           # Permutations, combinations, Pascal
└── module_05_geometry/                # Points, lines, rectangles
```

---

## 🧠 Core Patterns Covered

### 1️⃣ Number Theory
```
GCD: Euclidean algorithm
LCM: (a * b) // gcd(a, b)
Modular: (a + b) % m = ((a % m) + (b % m)) % m
```
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Count Primes | Medium | 204 |
| Ugly Number II | Medium | 264 |
| Perfect Squares | Medium | 279 |
| Pow(x, n) | Medium | 50 |

### 2️⃣ Digit Manipulation
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Palindrome Number | Easy | 9 |
| Reverse Integer | Medium | 7 |
| Add Digits | Easy | 258 |
| Happy Number | Easy | 202 |

### 3️⃣ Combinatorics
| Problem | Difficulty | LeetCode # |
|---------|------------|------------|
| Pascal's Triangle | Easy | 118 |
| Unique Paths | Medium | 62 |
| Factorial Trailing Zeroes | Medium | 172 |

---

## 💡 Key Formulas

```python
# GCD (Euclidean)
def gcd(a, b):
    while b:
        a, b = b, a % b
    return a

# Fast power
def power(x, n, mod):
    result = 1
    while n > 0:
        if n & 1:
            result = (result * x) % mod
        x = (x * x) % mod
        n >>= 1
    return result

# Sieve of Eratosthenes
def sieve(n):
    is_prime = [True] * (n + 1)
    is_prime[0] = is_prime[1] = False
    for i in range(2, int(n**0.5) + 1):
        if is_prime[i]:
            for j in range(i*i, n + 1, i):
                is_prime[j] = False
    return is_prime
```

---

**🚀 Start with `module_01_math_fundamentals` for core techniques!**
