# Prime


Write a program to check whether the given number is prime or not

Input:Positive number

Output: Display either "Prime Number" or "Not a prime"

Refer sample input and output for formatting specification.
Logic Test Case 1

Input (stdin)
7

Expected Output

Prime Number
Logic Test Case 2

Input (stdin)
10

Expected Output

Not a Prime



num =int(input())

# To take input from the user

#num = int(input("Enter a number: "))

# prime numbers are greater than 1

if num > 1:

   # check for factors

   for i in range(2,num):

       if (num % i) == 0:

           print("Not a Prime")

          

           break

   else:

       print("Prime Number")

       

# if input number is less than

# or equal to 1, it is not prime

else:

   print(num,"is not a prime number")
      
