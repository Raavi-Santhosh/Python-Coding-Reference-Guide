---
description: You will have an overview of single-line comments and multi-line comments
---

# Comments in Python

Programmers use comments to describe to viewers/readers what they are intending to do with the code they are writing. When comments are encountered by the Python interpreter, it simply ignores them during the execution.

### Single-line Comments

In python, single-line comments start with a pound symbol '\#'.

**Example:-**

```python
# This is my first comment
# This is also a comment
# If it is a single-line comment then it must start with a # symbol
# Comments are ignored by python interpreter during the execution
# Below line is to print Hello world!

print("Hello World!")
```

### **Multi**-line Comments

Any content which is enclosed between triple single quotes `'''<comments>'''` or triple-double quotes `"""<comments>"""` are multi-line comments. Triple quotes are generally used for multi-line strings but, they are also used as multi-line comments as well.

**Example:-**

```python
"""This is a 
multi-line comment using
triple double quotes"""

'''This is also a 
multi-line comment with triple
single quotes'''
```

They does not generate any extra code unless they are not **docstrings.**

> 💡 **Note:**   
> Docstrings are multi-line strings which are defined right after the declarations of functions, classes, or methods. _Refer Functions topic for more detail._

