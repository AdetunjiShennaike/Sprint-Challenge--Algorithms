#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)The runtime would be O(n), no matter what n.pow(3) is you're constantly adding n.pow(2) which is basically removing it from the equation. 
So every iteration is going to be the same as increasing 1 n value in a range of n.

b)The runtime would be O(n*k), because the first loop goes through for the entirety of n, which is O(n) and the inner loop every time will go through k iterations, 
which will always be smaller than n. The second loop isn't equal to log n, hence calling the output of the operation O(k)

as long as the loop is less than n it is going to be log(n)

c)The runtime is O(n), it will always recursively go through n times. Its the same runtime as an iterative loop like for(i=0;n>i;i++).

## Exercise II

Since you have no idea how much n is to begin with and where f is located, you would want to use the fastest way to figure out where f,
is so that you break the least amount of eggs. Take the number of floors (n) and divide it in half(k) and test if k is equal to f. 
If the egg breaks divide that half(k) in half(m) and check if m is equal to f, and if the egg doesn't break add n and k and divide that in half(h),
check if h is equal to f. Continuously do this until you find f. This runtime would equal O(log n)  
