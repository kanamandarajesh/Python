In Python, **conditions** and **operators** are fundamental for controlling program flow and making decisions. Here's a breakdown of each:

---

### 🧮 **Operators in Python**

Operators are special symbols or keywords that perform operations on variables and values.

#### **1. Arithmetic Operators**
These perform basic mathematical operations:

| Operator | Description        | Example     |
|----------|---------------------|-------------|
| `+`      | Addition            | `5 + 3` → `8` |
| `-`      | Subtraction         | `10 - 4` → `6`|
| `*`      | Multiplication      | `3 * 4` → `12`|
| `/`      | Division            | `8 / 2` → `4.0`|
| `%`      | Modulus (remainder) | `10 % 3` → `1` |
| `**`     | Exponentiation      | `2 ** 3` → `8` |
| `//`     | Floor division      | `10 // 3` → `3` |

#### **2. Comparison Operators**
Used to compare values and return `True` or `False`.

| Operator | Description               | Example      |
|----------|----------------------------|--------------|
| `==`     | Equal to                   | `5 == 3` → `False` |
| `!=`     | Not equal to               | `5 != 3` → `True`  |
| `>`      | Greater than               | `5 > 3` → `True`   |
| `<`      | Less than                  | `5 < 3` → `False`  |
| `>=`     | Greater than or equal to   | `5 >= 5` → `True`  |
| `<=`     | Less than or equal to      | `3 <= 5` → `True`  |

#### **3. Logical Operators**
Used to combine conditional statements.

| Operator | Description                     | Example               |
|----------|----------------------------------|-----------------------|
| `and`    | True if both conditions are True | `(5 > 3) and (3 < 8)` → `True`|
| `or`     | True if at least one is True     | `(5 > 3) or (3 > 8)` → `True`|
| `not`    | Inverts the truth value          | `not(5 > 3)` → `False`  |

#### **4. Assignment Operators**
Used to assign values to variables.

| Operator | Description                | Example      |
|----------|-----------------------------|--------------|
| `=`      | Assign                     | `x = 5`       |
| `+=`     | Add and assign              | `x += 3` (Same as `x = x + 3`) |
| `-=`     | Subtract and assign         | `x -= 2`      |
| `*=`     | Multiply and assign         | `x *= 4`      |
| `/=`     | Divide and assign           | `x /= 2`      |

#### **5. Membership Operators**
Check if a value is in a sequence.

| Operator | Description                | Example      |
|----------|-----------------------------|--------------|
| `in`     | True if value is found      | `'a' in 'apple'` → `True`|
| `not in` | True if value not found     | `'b' not in 'apple'` → `True`|

---

### ✅ **Conditional Statements**
Conditional statements allow decision-making in code execution.

#### **Basic Structure:**
```python
if condition:
    # Code to execute if condition is True
elif another_condition:
    # Code to execute if another_condition is True
else:
    # Code to execute if all conditions are False
```

#### **Example:**
```python
age = 20

if age >= 18:
    print("You are an adult.")
elif age >= 13:
    print("You are a teenager.")
else:
    print("You are a child.")
```

---

### **Combining Conditions**
You can combine multiple conditions using logical operators.

#### **Example:**
```python
score = 85
if score > 90 and score <= 100:
    print("Grade: A")
elif score > 75 or score == 75:
    print("Grade: B")
else:
    print("Grade: C or lower")
```

---

### **Ternary (Conditional) Operator**
Python supports a shorthand for `if-else`:

```python
# Syntax: result_if_true if condition else result_if_false
result = "Pass" if score >= 50 else "Fail"
```

---

Let me know if you need more details on any specific part!
