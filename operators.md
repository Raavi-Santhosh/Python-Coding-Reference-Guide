---
description: Take a quick look of operators in Python with a short example.
---

# Operators

![Different operators supported by Python](.gitbook/assets/operators.png)

## Arithmetic Operators

Arithmetic operators are used for performing mathematical operations like addition, multiplication, division, etc, and return the result which an arithmetic operator is calculated.

| Operator |                                                     Description | Example |
| :---: | :--- | :---: |
| + | Adds operands on either side of the operator | 3 + 2 = 5 |
| - | Subtracts right operand from the left operand | 5 - 2 = 3 |
| \* | Adds operands on either side of the operator | 2 \* 3 = 6 |
| / | Perform division operation. The result is a `Float` value | 12 / 5 = 2.4 |
| % | Performs modulo division. This will give us the Remainder | 7 / 4 = 3 |
| // | Performs Floor division. It returns the quotient if both the operands are positive.  If any of the operands is negative then it returns the floor value. i.e., rounded away from zero \(towards the infinity\) | 7//2 = 3 and 7.0//2.0 = 3.0, -11//3 = -4, -11.0//3 = -4.0 |
| \*\* | Power | 2 \*\* 3 = 8 |

## Comparison Operators

Comparison operators are used for comparing operands on either side of the operator. It returns `True` or `False` based on the condition.

| Operator |                                                        Description | Example |
| :---: | :--- | :---: |
| &gt; | Greater than - `True` if the left operand is greater than the right operand | 5 &gt; 3 |
| &lt; | Less than - `True` if the left operand is less than the right operand | 2 &lt; 6 |
| &gt;= | Greater than or Equal to - `True` if the left operand is greater than or equal to the right operand | 2 &gt;= 2 |
| &lt;= | Less than or Equal to - `True`  if the left operand is less than or equal to the right operand |  3 &lt;= 3 |
| == | Equal to - `True` if  both operands are exactly equal  |  6 == 6 |
| != | Not Equal to - `True` if operands are not equal | 5 != 4 |

## Logical Operators

`and`, `or` and `not` are Logical Operators.

| Operator |                                                       Description | Example |
| :---: | :--- | :---: |
| and | Logical AND - `True` if both the operands are `True` | x and y |
| or | Logical OR - `False` if both the operands are `False` | x or y |
| not | Logical NOT - `True` if the operand is False and vice versa | not x |

### Logical AND Operator

The result of the Logical AND operator is`True`if both the operands are `True`. See the below truth table

| Operand 1 | Operand 2 | Result |
| :---: | :---: | :---: |
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

### Logical OR Operator

The result of the Logical OR operator is`False`if both the operands are `False`. See the below truth table

| Operand 1 | Operand 2 | Result |
| :---: | :---: | :---: |
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |

### Logical NOT Operator

Logical NOT is a complementary operator. If the operand is`True`then the result of logical NOT operator is`False`and vice versa. Check out the below truth table.

| Operand | Result |
| :---: | :---: |
| Not True | False |
| Not False | True |

{% hint style="success" %}
Comparison operators and logical operators are chained up to form an expression and are most frequently used in conditional statements. 
{% endhint %}

## Bitwise Operators

Bitwise Operators work on bits as they operate on operands bit by bit.

| Operator | Description | Example |
| :---: | :--- | :---: |
| & | Bitwise AND  |  |
| \| | Bitwise OR |  |
| ^ | Bitwise XOR |  |
| ~ | Bitwise Not |  |
| &gt;&gt; | Bitwise Right-shift |  |
| &lt;&lt; | Bitwise Left-shift |  |

## Assignment Operators

## Special Operators

Python offers some special type of operators. Membership operators & Identity operators.

### Membership Operators

Membership operators are used for checking whether a value is present in the sequence like list, string, tuple, dictionary, set.

 `in` and `not in` are Membership Operators.

| Operator |                                                        Description | Example |
| :---: | :--- | :---: |
| in  | `True` if the value present in the sequence and `False` otherwise. | 5 in \[2,4,5,6\] |
| not in  | `True` if value not present in the sequence and `False` otherwise. | 7 in \[2,4,5,6\] |

### Identity Operators

Identity operators are used for comparing the memory location of two objects.

`is` and `is not` are the Identity Operators.

| Operator |                                                      Description | Example |
| :---: | :--- | :---: |
| is | `True` if operands on either side of the operator points to the same object and `False` otherwise. | x is y, similar to id\(x\) == id\(y\) |
| is not  | `True` if operands on either side of the operator does not points to the same object and `False` otherwise. | x is not y, similar to id\(x\) != id\(y\) |

#### Difference between Identity Operator & Equal-to comparison Operator









