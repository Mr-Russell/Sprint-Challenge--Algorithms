#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Liner
      The function contains a while-loop whose runtime directly correlate to the value of n


b) Polynomial
      There are 2 loops, and the runtime of each loop depends on the value of n


c) Liner
      The function calls itself, decrementing the value each time. Therefore  the runtime directly correlates to the value of n

## Exercise II


I believe the best way to solve this problem is with a Binary Search Tree. 

Using this method, you would start at the middle floor (n//2) and drop an egg from there. If the egg cracks, you would then count the floor you dropped from as the new value for n, and repeat the process.

If the egg does not crack, you would then count the floor above where you dropped from as the new "ground floor", and repeat the process.  

This process would keep repeating until you have found the upper-most floor where an egg does not crack after being dropped (floor f). A Binary Search Tree has a higher likelihood of reducing the attempts necessary to finding floor f as every attempt halves the amount of floors left to test. This would most likely reduce the amount of cracked eggs while testing