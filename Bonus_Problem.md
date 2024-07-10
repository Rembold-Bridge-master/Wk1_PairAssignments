# Bonus Problem - Longest No Repeats

This problem is purely optional, in case you zip through the other problems particularly quickly.

The `english.py` library is imported into the top of the template for this problem to give you access to `ENGLISH_WORDS`, which is a list of all the words in the English dictionary. This is something you can iterate through, so for example
```python
for word in ENGLISH_WORDS:
  print(word)
```
would individually print each word to the console.

Your task here is to write a program that finds and prints to the console the longest word in the English dictionary which contains no repeated letters. That is to say, where no single letter shows up multiple times anywhere in the word. The word `"single"` for instance, would fit this requirement, but the word `"repeating"` would not, as the letter `e` shows up twice.
