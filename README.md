# 4.02-for-loops

## Part 1
Write a function `pluralize_words()` that takes in a list of words as an argument and updates the values of the list to make each one plural. It should return nothing (update the list in place). 

Making plurals in English has a number of special cases, but for this lab we'll use a simple rule: if a word ends in 'y' remove the 'y' and add 'ies'; otherwise, add an 's'.

We'll test the function on a list of words.

1. Create the function contract for `pluralize_words()`
2. Provide a few example lists that confirm `pluralize_words()` works.
     * Include examples with words like "berry"
     * What if the list is empty?
     * What happens if a word ends in "s"?
     * If the word ends in 'y' but the letter before the 'y' is a vowel--like in 'attorney'--the 'y' should stay and an 's' is added (attorneys).

### Example
Example of the file:
```python
# contract goes here
def pluralize_words(word_list):
  # your code goes here

word_list = ['apple', 'berry', 'melon']
print(f"Singular words: {word_list}")

pluralize_words(word_list)
print(f"No longer singular words: {word_list}")

# test more examples here
```

Example output:
```
Singular words: ['apple', 'berry', 'melon']
No longer singular words: ['apples', 'berries', 'melons']
```

### Hint
Remember that you can index into the string and get the length of a string. Use that to get the lass letter of each word

## Part 2
Create a function `my_reverse()` which will return a reversed string.
1. Create the function contract for `my_reverse()`
2. Provide a few examples that confirm `my_reverse()` works:
   * An empty string
   * A string of even length
   * A string of odd length greater than 1
   * A string of length 1

### Example
Example of the file:
```python
# contract goes here
def my_reverse(string_to_reverse):
    # your code goes here
reversed = my_reverse('apples')
print(reversed)
# test more examples here
```

Example output:
```
>>> python3 my_reverse_lab.py
selppa
```

### Hint
To get the last element: `(len(my_list) -1) - 0`
To get the second to last element: `(len(my_list)-1 ) - 1`
To get the third to last element: `(len(my_list)-1) - 2`

## Bonus!
Create a function `reverse_strings_in_list()`. This function will take a list of strings you want to reverse and return a list of all the reversed strings.

   
   
