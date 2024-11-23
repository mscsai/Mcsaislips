a). Write a python program to print the multiplication table for the given 

number? 

Code:

 # Python program to find the multiplication table (from 1 to 10) of a 

number input by the user # take input from the user 

num = int(input("Display multiplication table of? ")) 

 # use for loop to iterate 10 times

for i in range(1,11): 

 print(num,'x',i,'=',num*i)


 (b). Write a python program to check whether the given number is prime or 

not? 

Code:

# Python program to check if the input number is prime or not 

#num = 407 

# take input from the user 

num = int(input("Enter a number: ")) 

# prime numbers are greater than 

1 if num > 1: rem=1 

 

 for i in range(2,num): 

 rem=num%i if 

rem == 0: 

 break 
  if rem == 0: 

 print(num,"is not a prime number") 

else: 

 print(num,"is a prime number") 

 

# if input number is less than # 

or equal to 1, it is not prime 

else: 

 print(num,"is not a prime number") 
 
