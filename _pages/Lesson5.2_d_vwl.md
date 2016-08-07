---
layout: page
title: Project 5 🛠 d_vwl
---

## A quick note on `return` vs. `print`

<code>print</code> just shows the human user a string representing what is going on inside the computer. The computer cannot make use of that printing. <code>return</code> is how a function gives back a value. This value is often unseen by the human user, but it can be used by the computer in further functions.

On a more expansive note, <code>print</code> will not in any way affect a function. It is simply there for the human user's benefit. It is very useful for understanding how a program works and can be used in debugging to check various values in a program without interrupting the program.

> ## Print is for people. Remember that slogan. Printing has no effect on the ongoing execution of a program. It doesn’t assign a value to a variable. It doesn’t return a value from a function.

## Remove the Vowels

<span class="mega-octicon octicon-file-code"></span>
<kbd>In your IDE, create a file called <mark>de_vowel</mark></kbd>

Create a function, `de_vowel`, which will take a string as input and return a copy of that string with all the vowels removed. Otherwise, the string should be the same.

1. Create the function contract for `de_vowel`.

```python
def de_vowel(string):
"""
A function contract explains what the function does. So, in this case, yours might look like:

#This function takes a string as an input and returns a copy of the string with the vowels removed.

Write `de_vowel` using a for loop
Provide a few examples that confirm de_vowel works as expected:
	* What if the string is all vowels ('aeiou')?
	* What if there are no vowels ('rdcls')?
	* What if some of the vowels are capital and some are lowercase ('lIKe ThIs?')
	* What if there is a mix of vowels and non-vowels and spaces ('this is silly')?
"""
```

Example:

```python
def de_vowel(a_string):
	# your code goes here
no_vowels = de_vowel("This sentence has no vowels")
print(no_vowels)
# examples go here
```

Example output:

<iframe src="https://trinket.io/embed/python/5238cab7c2?outputOnly=true&runOption=run&start=result" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### Review Adding Strings

Now, before your `d_vwl`'d sentence, add a string explaining what's happening. Like this:

```python
Here is your sentence without vowels: Hr s yr sntnc wtht vwls
```

### Bonus!

Use a counter (variable you define outside of a loop to keep track of a value inside a loop) to create a function `count_vowels`.

`count_vowels` takes in a string and returns an int representing the number of vowels in the string.
