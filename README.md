# NEEB-Python-project

# Question 1:
Write a program that prints numbers from 0 to 99.

Numbers must be separated by ,, followed by a space
Numbers should be printed in ascending order, with two digits
The last number should be followed by a new line
You can only use no more than 2 print functions with string format
You can only use one loop in your code
You are not allowed to store numbers or strings in a variable
You are not allowed to import any module
# Question 1 Python code:

# create a for loop for numbers(i) within the range of 100 
for i in range(100):

# print each numbers within the range of 100 in two digits format followed by comma and space
	print(f"{i:02}", end='' + ',' + ' ')
	
# write an if statement to check if value of i is greater than or equal to 99
	if  i >= 99:
# if condition is met print a newline character
		print()
  
	
# Question 2: 
Write a function that prints a string in uppercase followed by a new line.

Prototype: def uppercase(str):
You can only use no more than 2 print functions with string format
You can only use one loop in your code
You are not allowed to import any module
You are not allowed to use str.upper() and str.isupper()
Tips: ord()

# Question 2 python code:

# define the function uppercase for character (str)

def uppercase(str):
  
 # create a loop to iterate through the character
    for char in str:

#  convert the character to uppercase using ASCII, then print character
    	 if 'a' <= char <= 'z':
    	 	print(chr(ord(char) - 32 ))
 
    	 else:
    	 	print(char)
    	 	
#  create an input fuction to allow user enter letter
letter = input('your letter:')
uppercase (letter)
# print new line
print()

