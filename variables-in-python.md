---
description: >-
  In this short note, you will have a quick glimpse of what a variable is? How
  to declare and initialize a variable, and we'll end with rules & regulations
  to name a variable.
---

# Variables

* Variables are like containers that hold the data in them for later use.
* We can also modify the values in the variable later.

**Example:-**

```python
 age = 25 # Declaring & Assigning value to variable
```

Here, `age` is a variable name that holds the value `25` .

> \*\*\*\*💡 **Note:**  
> In Python we don't store values in variable. Rather variable will store the reference/memory address of the value. That means, variable will points to the reference of the value.

> Python is a dynamically typed programming language. So there is no need to mention the type of the variable we are trying to assign, like we usually do in statically typed programming langauge like C, C++, C\#, Java etc.,

### Assigning Multiple values to Multiple variables in a single line

```python
 var1, var2, var3 = 1, 3.45, "Hello"
```

No. of variables must be the same as the no. of values you are trying to assign. If not you will get `ValueError`. Have a look at the below examples.

**Example 1:-**

```python
 var1, var2 = 1, 3.45, "Hello" # No.of variables are less than the no. of values
 ---------------------------------------------------------------------------
 ValueError                                Traceback (most recent call last)
 <ipython-input-2-dd7f0ca9cce5> in <module>
 ----> 1 var1, var2 = 1, 3.5, "hello"
 ​
 ValueError: too many values to unpack (expected 2)
```

Here, it requires 3 variables to assign 3 values but, we have provided only 2 variables. Therefore result in `ValueError: too many values to unpack`

**Example 2:-**

```python
 var1, var2, var3, var4 = 1, 3.45, "Hello" # No.of variables are more than the no. of values
 ---------------------------------------------------------------------------
 ValueError                                Traceback (most recent call last)
 <ipython-input-4-51b9aae0e19e> in <module>
 ----> 1 var1, var2, var3, var4 = 1, 3.5, "hello"
 ​
 ValueError: not enough values to unpack (expected 4, got 3)
```

In the above example, we have to assign 4 values to 4 variables but we supplied only 3 values which leads to `ValueError: not enough values to unpack`

### Assigning a Single value to Multiple variables in a Single line

```python
 var1 = var2 = var3 = var4 = "hello"
```

All the variables \(var1, var2, var3, var4\) will point to `"hello"` value in the memory.

### Pythonic Way of Swapping Two Variables

Unlike the traditional way of swapping values in two variables using an additional temporary variable as in C, C++... Python does it in a much more simple approach in just a single statement as shown below.

```python
 var1 = 3
 var2 = "hello"
 ​
 var1, var2 = var2, var1
```

### Rules & Regulation while naming the Variables

Every programming language will follow set-of rules for naming the variables. Python too has some protocols which have to be followed while naming the variables that are listed below.

1. Python is a case sensitive language so variable name `age` is different from `Age`.
2. A variable name cannot have special characters like .,\`~@\#$%, etc, other than \_ \(underscore\).
3. A variable name can have lowercase letters, uppercase letters, and digits \(0-9\).
4. Variable name should not start with a digit but can start with an underscore \( \_ \).
5. If a variable name starts with a single underscore then programmers will treat it as a private variable and they don't mess with that variable.
6. If a variable name starts with a double underscore then it is treated as a strong private variable
7. If a variable starts and ends with a double underscore then it is an in-build defined attribute like `__doc__`, `__len__` , etc.,
8. Follow the following naming conventions for better readability and understanding of the program.
   1. snake\_case
   2. MACRO\_CASE
   3. camelCase
   4. CapWords
9. As python is dynamically typed and there is no special keyword to define constants like in C, C++, so use capital letters for constants so that other programmers avoid modifying it.

