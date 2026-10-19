
# 🗂 Data Structures & Algorithms Example: Stack & Balanced Parentheses

This Python script demonstrates the use of the **Stack data structure** to check **balanced parentheses, brackets, and braces** in an expression.  
It’s a classic **Data Structures & Algorithms (DSA)** problem used in programming, interviews, and real-world parsing tasks.

---

## 🚀 Features

- ✅ Implements a **custom Stack** class in Python  
- ✅ Checks for **balanced parentheses, brackets, and braces**  
- ✅ Handles nested and complex expressions  
- ✅ Supports expressions with other characters (letters, numbers, operators)  
- ✅ Easy to extend for other parsing problems  

---

## 📦 Requirements

- `Python 3.x ` 

No additional libraries are required as the implementation uses **core Python**.

---

## ⚙ How It Works

1. **Stack Implementation**  
   - `push(item)` → Adds element to top  
   - `pop()` → Removes and returns top element  
   - `peek()` → Returns top element without removing  
   - `is_empty()` → Checks if stack is empty  

2. **Balanced Parentheses Algorithm** 
   - Traverse each character of the expression  
   - Push opening symbols `(`, `[`, `{` onto the stack  
   - On closing symbols `)`, `]`, `}`, check if the top of the stack matches  
   - If mismatch or leftover elements → expression is **not balanced**  
   - Otherwise → **balanced** 

---

## 🔧 Example Usage

```python
print(is_balanced("()"))               # True
print(is_balanced("([)]"))             # False
print(is_balanced("((()))[{}]"))       # True
print(is_balanced("((()))[{}]]"))      # False
print(is_balanced("a + (b * c) - {d / [e + f]}")) # True
print(is_balanced("((a + b) * (c - d)"))  # False
```
---

## 📊 Complexity Analysis

- **Time Complexity**: O(n) → n = length of expression

- **Space Complexity**: O(n) → Worst-case stack size (all opening symbols)

---

## 💡 Why This Is Useful

- Core **DSA concept**: Stack
- Common in **parsing, compiler design, expression evaluation**
- Often asked in **technical interviews**
- Foundation for more **advanced algorithms** like infix-to-postfix conversion
---

## 🛠 Extending the Script

- Add support for **custom symbols**
- Integrate into **expression evaluators** or **mini calculators**
- Visualize **stack operations** for educational purposes
- Combine with **queues or trees** for complex parsing algorithms

---
