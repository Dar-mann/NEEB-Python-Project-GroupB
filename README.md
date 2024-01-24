# NEEB-Python-project
# Question 2: 
Write a function that prints a string in uppercase followed by a new line.

Prototype: def uppercase(str):
You can only use no more than 2 print functions with string format
You can only use one loop in your code
You are not allowed to import any module
You are not allowed to use str.upper() and str.isupper()
Tips: ord()

# PYTHON PROGRAM
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
print('\n')
