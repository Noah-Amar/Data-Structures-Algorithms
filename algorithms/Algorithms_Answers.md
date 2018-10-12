Add your answers to the Algorithms exercises here.

**Exercise I**:

a) O(n)

b) O(n^4)

c) O(n)


**Exercise II**:
Start at floor n/2 and drop the first egg
If it does not break, move up halfway between the current floor and highest floor and drop the next egg
Else if it does break, move down halfway between the current floor and lowest floor and drop the next egg
Continue testing the eggs through this process until you have found floor f where the egg does not break and the floor above (f+1) does break