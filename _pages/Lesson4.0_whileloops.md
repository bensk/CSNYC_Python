---
layout: page
title: Lesson 4 👉 <code>while</code> loops
---

## Do Now
```python
# what do you think this will do?
n=1
while n>0:
  print n
  n = n+1
```

~~bad stuff~~
infinite loop! [^pycharm]

[^pycharm]: PyCharm will stop these for you. You can also use `ctrl+c` to stop it in the command line.

## ✍ while Loop
Code that repeats while a condition is true.

```python
x=1
while x in range(0,4):
  print x
  x = x+1
```

Let's take a closer look:

```python
n=1 # sets n to 1. What happens if we don't?
while n>0:
 print n
 n = n+1
# Predict!
while True:
  print "whoa"
# What about this? What gives?
while x<5:
  print x
  x = x + 1

```

## Countdown v2.0

Write a program called `countdownV2.py `

It takes any number as input, starts counting down and ends with a BOOM! (or similar exclamation.)  

It should look like this:

    Enter number: 10
    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    BOOM!
