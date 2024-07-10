# Problem 3: Biggest Two

In this problem your task is to write a program that reads in integers from a _user's input_ up until they enter a blank line, at which point the program should print out the largest and second-largest values from all the integers that the user had input. You can assume that at least two integers will always be entered, but you can **not** assume they will always be positive. For example, running the program might result in the following being printed to the screen:

```text
This program finds the two largest integers entered.
Enter a blank line to stop.
  ? 223
  ? 251
  ? 317
  ? 636
  ? 766
  ? 607
  ? 607
  ? 
The largest value is 766.
The second-largest value is 636.
```

The values entered for this sample run are the number of pages in the British hardcover editions of J.K. Rowling's _Harry Potter_ series. The output tells us that the longest book is _Harry Potter and the Order of the Phoenix_ at 766 pages, and the second-longest book is _Harry Potter and the Goblet of Fire_ at 636 pages.

You should write your program so that it exactly duplicates the format above, with the instructions, prompt, and final output looking the same. You can (and should) of course enter in whatever numbers you like when testing it (including negative numbers!)

_Hint: While you **could** keep track of every number entered by the user, you only ever really need to track two: the largest and second largest..._
