# Problem 2: Textual Pyramids

Here your goal is to write a program which uses the `HEIGHT` variable defined at the start of the template to draw a pyramid to the console. The pyramid should be constructed of `*` characters and have a number of lines equal to the desired `HEIGHT`. The width of each row should increase by 2 as you move downward in the console, toward the base of the pyramid. Each of the rows should be centered with respect to the others, and the bottom line should begin immediately at the left margin.

As an example, if the value of `HEIGHT` as 8, then your program should print the following pyramid to the console:
```text
       *
      ***
     *****
    *******
   *********
  ***********
 *************
***************
```
Notice how on the bottom row the pyramid starts immediately, with no space between it and the left margin, and that each row of the pyramid is centered on the others, increasing by 2 each time.

You should ensure that if the value of `HEIGHT` is changed to something else, your code behaves appropriately, drawing a correct pyramid of that height.

_Hint: To keep things centered, you are going to need an amount of space characters before the starting # on most lines. How could you assemble these strings? How will you know how many space characters (and # characters) to add?_
