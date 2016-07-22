---
layout: "post"
title: "Getting Loopy"
date: "2016-05-06 23:36"
---

## Do Now

<span class="mega-octicon octicon-file-code"></span>
In PyCharm, create a file called `May 6 Do Now_String Slicing`

```python
# Run the code below, and write a comment explaining what it does:
print "hello"[1:]
print "hello"[:4]
print "hello"[2:4]
```
Using `"string"[a:b] ` syntax – print:

1. `"it"` from "GitHub"
2. `"burger"` from "Hamburger"
3. `"on" ` from "dongle"
4. `"nap"` from "Snapchat"

In a comment: `"string"[a:b]` is called "slicing" a string. Why do you think it's called that?

---

<span class="mega-octicon octicon-file-code"></span>
In PyCharm, create a file called `getting_loopy`


## Part 1
Write a function `fruit_pluralizer`. It will take in a list of fruit and return nothing. The function should update the values of the list so that the values are plural. If the fruit name ends in a 'y' remove the 'y' and add 'ies', otherwise add an 's'.

1. Create the function contract for `fruit_pluralizer`.
2. Provide a few examples that confirm `fruit_pluralizer` works as expected:
	* Include examples with 'berry'
	* What if the list is empty?
	* What if the fruit ends in 's'?

### Example

```python
# contract goes here
def fruit_pluralizer(list_of_strings):
	# your code goes here
fruit_list = ['apple', 'berry', 'melon']
print("Single Fruit: " + str(fruit_list))
fruit_pluralizer(fruit_list)
print("No longer single Fruit: " + str(fruit_list))
# examples go here
```

Running the code:

```python
Single Fruit: ['apple', 'berry', 'melon']
No longer single Fruit: ['apples', 'berries', 'melons']

```

### Hint
Remember that you can index into the string and get the length of a string. Use that to get the last letter of each word.

---

## Part 2
Create a function `my_reverse`, which will return a reversed string.

1. Create the function contract for `my_reverse`.
2. Provide a few examples to confirm that `my_reverse` works:
	* An empty string
	* A string of even length
	* A string of odd length greater than 1
	* A string of length 1

### Example

```python
# contract goes here
def my_reverse(string_to_reverse):
	# your code goes here
reversed = my_reverse("apples")
print(reversed)
# examples go here
```

Running the code:

`selppa`

### <span class="mega-octicon octicon-light-bulb"></span> Hints

```python
# To get the last element:
(len(my_list) -1) -  0
#To get the second to last element:
(len(my_list)-1 ) - 1
#To get the third to last element:
(len(my_list)-1) - 2
```

### Bonus!
Create a function `reverse_strings_in_list`. This function will input a list of strings you want to reverse. The function will reverse the strings in the list by calling the `my_reverse` function in a loop.
