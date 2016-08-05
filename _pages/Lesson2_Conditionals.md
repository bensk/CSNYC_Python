---
layout: page
title: Lesson 2 👉 Conditionals
---

## ⏳ Datatypes Review
So far we've seen data in 3 forms:

| Datatype | Example                | Explanation                         |
|:---------|:-----------------------|:------------------------------------|
| Numbers  | `yourAverage = 3.8`    | Integers or floats                  |
| Strings  | `myName= "Ben"`        | Anything inside "quotes"            |
| Booleans | `isItSaturday = False` | <kbd>true</kbd> or <kbd>false</kbd> |

## ✍ Conditionals
Conditional <sup>(n) </sup>: a statement that is true IF something else is true
“If…then…” statements

_In programming:_    
**If** this functions, do ___________    
**Else**, do ___________

_In life:_
**If** you do your homework, then you will earn a high grade.    
**Else**, you will earn a low grade.

### What do conditionals require in order to function?

```python
if #something true:
    # run this code
else:
    #run this code
```

**Booleans!**

```python
"""
What will print after each conditional is run?
"""
# Number 1:
if 5<2:
    print "I am right"
else:
    print "I am wrong"

    # Number 2:
if 5>2:
    print "I am right"
else:
    print "I am wrong"
```


## Comparators

| Comparison               | Symbol |
|:-------------------------|:------:|
| Equal to                 |   ==   |
| Not equal to             |   !=   |
| Less than                |   <    |
| Less than or equal to    |   <=   |
| Greater than             |   >    |
| Greater than or equal to |   >=   |

## ❗ Pop Quiz!
<small>That you are writing</small>

```python
harry_potter = raw_input("What's Harry Potter's middle name?")
if harry_potter.lower() == "james":
   print "You're ok"
else:
   print "Expeliarmus!"

grace_hopper = raw_input("Grace Hopper coined what Computer Science term? A) Byte, B) Bug, C) Iterate, D) Function")
if grace_hopper.lower() == "b":
   print "You remembered!"
else:
   print "No! You make me sad..."
```
