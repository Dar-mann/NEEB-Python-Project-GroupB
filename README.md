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

for i in range(100):
	print(f"{i:02}", end='' + ',' + ' ')
	if  i >= 99:
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

def uppercase(str):
    for char in str:
    	 if 'a' <= char <= 'z':
    	 	print(chr(ord(char) - 32 ))
    	 else:
    	 	print(char)
letter = input('your letter:')
uppercase (letter)
print('\n')
