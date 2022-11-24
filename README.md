# Code challenges

## Problem 1: Polygon Optimisation
Let us consider the following set of points:

points = [(1, 1), (1, 2), (1, 3), (2, 3), (2, 4), (3, 4), (3, 3), (3,2), (2,2), (2,1), (1,1)]

The goal of the exercise is to reduce the previous set of points to keep the
necessary points to draw the same Polygon.

a) Find the points that are not needed to draw the Polygon and explain why.

b) Write a function that, given a Polygon's path of points, returns a reduced list that
defines the same Polygon. (Notice that all the points in the set are adjacent).


## Problem 2: Incorrect syntax with brackets

a) Given a string made of opening and closing brackets, how to check if its syntax is OK?
Choose the language you want to answer this question and comment on the code
explaining each step.
Examples: ()(()()) is correct, ()))) is not, )( is not

b) Follow-up questions (code not needed, just explain what you would do)

i) How would you do it with multiple bracket types (), {}, [], '', ""

ii) How to use that to correct real code syntax with not only brackets but letters,
numbers etc? (e.g.: ((a) → (a) )
