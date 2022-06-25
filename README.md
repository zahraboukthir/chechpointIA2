# chechpointIA2
Objective
 
In this checkpoint, we'll be testing your Python skills! 

Question 1

Write a program that will find all numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a list.

Hint: Consider using the range(#begin, #end) method.
 

Question 2 

 Write a program that can compute the factorial of a given number. (The factorial of n is the product of all positive integers less than or equal to n.) For example: For factorial(5)= 5 x 4 x 3 x 2 x 1 the result is 120 (i.e. factorial (0)=1).

Question 3 

With a given integer number n, write a program to generate a dictionary that contains (i, i*i) such that is an integral number between 1 and n (both included). Then, the program should print the dictionary. Suppose the following input is supplied to the program: 8 Then, the output should be: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}  

Question 4 

Given a non-empty string and an integral n, return a new string where the char at index n has been removed. The value of n will be a valid index of a char in the original string (i.e. n will be in the range 0..len(str)-1 inclusive). 

missing_char('kitten', 1) → 'ktten'    for example here we remove "i" which is located in the index 1

missing_char('kitten', 0) → 'itten'   here we remove "k" which is in the index 0

missing_char('kitten', 4) → 'kittn'   here we remove "e" which is in the index 4

Question 5 

Write a NumPy program to convert a NumPy array into a Python list structure.

Expected output: 

Original array elements: [[0 1] [2 3] [4 5]] 

Array to list: [[0, 1], [2, 3], [4, 5]] 
 

Hint: We can use the to_list() function to ensure the conversion.

Question 6

Write a NumPy program to compute the covariance matrix of two given arrays. 

Original array1: [0 1 2] 

Original array2: [2 1 0] 

Covariance matrix of the said arrays: [[ 1. -1.] [-1. 1.]]
 

Hint: We can use the np.cov() function to calculate the covariance between these two arrays

Question 7

Question: Write a program that calculates and prints the value according to the given formula: Q= Square root of [(2 * C * D)/H] 

The following are the fixed values of C and H: C is 50. H is 30. 

D is the variable whose values should be input into your program in a comma-separated sequence. (That means D contains more than value)

Example: Let's assume the following comma-separated input sequence is given to the program: 100,150,180 The output of the program should be 18,22,24 

To further explain this, we will obtain a result for each value of D:  Q1= Square root of [(2 * C * 100)/H] =18, Q2= Square root of [(2 * C * 150)/H] = 22 and Q3 = Square root of [(2 * C * 180)/H]  = 24

Hint: If the output received is in decimal form, it should be rounded off to its nearest value. For example, if the output received is 26.0, it should be printed as 26. In case of input data being supplied to the question, it should be assumed to be a console input. 
