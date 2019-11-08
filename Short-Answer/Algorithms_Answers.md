#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) a = 0 while (a < n * n * n):0(n3) a = a + n * n 0(c)

Ans : This program has a runtime of 0(n). While loop will run nnn/nn times since in each iteration of while loop, a is incremented by nn times.


b)sum = 0 0(c) for i in range(n): 0(n) i += 1 for j in range(i + 1, n): 0(n) j += 1 for k in range(j + 1, n):O(n) k += 1 for l in range(k + 1, 10 + k):10 l += 1 sum += 1

Ans : we have 4 nested for loops. Top three are linear with n, but last one runs 10 times each time. So the total runtime will be nnn10=10nnnn we will ignore the constant 10 so it will be 0(n**3)

c)def bunnyEars(bunnies): if bunnies == 0: 0(c) return 0 0(c)

    return 2 + bunnyEars(bunnies-1) O(n) 

    Ans : This is a recursive function call, with one function call per recursion. So if there are 4 bunnies then the function is recursively call for 3, 2,1 bunny respectively. Hence It will be a linear function of n.

## Exercise II


floor = O broken= False while is not broken; floor+= 1 if egg breaks we exit the loop and return floor -1. O(n)