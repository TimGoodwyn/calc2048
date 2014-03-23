2048 for the Casio calculator language.

This language doesn't allow comments... (AFAIK)

I have used * where the multiply symbol is used in the real language

Disclaimer: I have copy-typed this from my calculator, so I may have made mistakes or omitted/added parts and forgotten to update the other.

Explanation of code
 - 2048SETC basically acts to flip the matrix so that you can iterate over cols/rows I and J and not care whether you're iterating up, down, left, right. This seemed slightly better than having 4 very similar branches for the move code.

TODO:
 - Remove debug printing
 - Implement quit properly, and add a "continue" option?
 - Detecting lose (probably won't bother)
 - Add indents to code in git?
 - Bug: fix redraw issue where e.g. 2 replaces a 16 you see "26"
