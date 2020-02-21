#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) For this while loop the running time is O(n). This is because the execution of the loop directly depends on the value of n each time


b) The inner loop doubles every time we run it until it hits its maximum of n, therefore running time complexity is O(nlog(n)). The while loop is O(logn). For loop is O(n). Multiplied we get O(nlogn)


c) Because of recursion on the last line that recalls function every time bunnies changes value the running time complexity is O(n)

## Exercise II

1. From the middle floor drop an egg 
2. If it breaks then the middle floor if f or higher than f. This means floor f is one of the lower half floors
3. If the egg does not break it means floor f is part of the top half of floors
4. Depending on what happens to the first dropped egg we repeat step 1 on the top or bottom half of floors until we determine floor f

Running time complexity for this algorithm will be O(logn) since half of the floors are eliminated after each try
