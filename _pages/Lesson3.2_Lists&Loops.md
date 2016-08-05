---
layout: page
title: Lesson 3.1 👉 Lists & Loops
---

## ✍ Let’s Iterate
How could we use lists and loops to calculate our average?

```python
grades = raw_input("What are your grades?").split()
float_grades=[] # Make an empty list.

for _______ in _______: # Make a for loop
    num_grade = float(_______)  # turn my inputs into numbers
    float_grades.append(num_grade) # add them to the empty list

average = sum(float_grades)/len(float_grades)

print "Your average is a " + str(average)
```

## ✍ List Splitting
```python
words = raw_input("Give me a bunch of words").split()
print words
print words[2]


['This', 'is', 'a', 'bunch', 'of', 'words']
a
```
