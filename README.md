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

