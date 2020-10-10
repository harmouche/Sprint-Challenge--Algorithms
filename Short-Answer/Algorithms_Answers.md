#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)
    While operation is O(n)
    n*n*n operation is O(n)
    n*n   operation is O(n)


b) O(n^2)
    O(n^2) is the worst case scenario. it can be O(nlogn), if "while j" can reduce the number of iterations.

c) O(n)
   it looks constant, but the recursive operation will run n times.

## Exercise II


Assumption:
since we are searching for a flor in a building, I will assume that the floor are sorted.

Psuedo Code:
Use Binary Search techneaque to find out the "f" floor.
1- divide the number of floors in half
2- start from the middle floor, through an egg
3- if broken divide the lower half if the "lower floors" in half
   if it did not break, divide the "upper floors" in half
4- repeat step 2 & step 3 till you find the highest floor where eggs don't break.
