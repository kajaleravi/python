**what is python?**
- python is simple and easy
- free and open source
- high level language
- portable
- Developed by Guido van rossum


**Python Character set**
- letters - A to Z, a to Z
- digits - 0 to 9
- special symbols - -+-*/ etc
- whitespaces - Blank space, tab, carriage return, newline, formfeed
- other Characters - python can process all ASCII and unicode Character as part of data or literals


**Variables**
    A Variable is name given to a memory location in a program.
    var = value
    name = ravi     (here, = assingment operator)



**Rule for identifiers**
    - identifiers can be combination of uppercase and lowercase letters, digits or an underscores.
        so myVariable, variable_1, variable_for_print all are valid python identifiers.
    - An identifier can not start with digit. So while variable_1 is valid, 1variable is not vaild.
    - we cannot use special symbols like !,@,#,$,% etc in our identifier.
    - identifier can be of any length.


**Data Types**
 - Integers (25, -25, 0)
 - String ("heelo" 'helo' '''hello''')
 - Float (decimals)
 - Boolean (True, False)
 - None (a = None)
 
 
**Operators**
  arithmetic: +,-,*,/,//,%,**
  relational/comparison: ==, !=, >, <, >=, >=
  assignment : = , -=, *=, /=, %=, //=, **=
  Logical: not, and, or
  Membership: in, not in
  Identity: is, is not
  Bitwise: &, |, ^
 
 
 **keywords**
 - Keywords in Python are reserved words that have a special meaning and purpose. They are used to define the syntax and structure of the Python language.
 
 **types of tokens**
 Punctuators:
 - are symbols to organize sentence structure in programming. 
  (), {}, @, [], #, etc
  agumented assigned operators are aslo punctuators: -=, +=, /= , *=, //=, = etc
  
  
  **expression execution**
  
  - String and numbers values can operate together with *
	A,B = 2,3
  Txt = "@"
 	print (2*Txt*3) #output = @@@@@@
  
  - String and string can operate with + 
   	A,B = "2",3
   	Txt = "@"
   	print((A+Txt)*B #output = 2@2@2@
   	
  - Numeric values can operate with all arithmetic operators
  	A,B = 2,3
  	C = 4
  	print(A+B*C) #output = 14
  	
  - Arithmetic expression with integer and float will result in float
  	A,B = 10,5.0
  	C = A*B
  	print(C)  #output = 50
  
  - Remainder is negative when denominator is negative
  
  
  
 Comments in Python:
  #single line comment
  
  """ This is 
  a multiline 
  comment """
  


  Inputs in python
  - input() statement is used to accept values (using keyboard) from user
  	- string input
  		name = input("name : ")
  	
  	-int input
  		age = int(input("age : "))
  		
  	-float input
  		price = float(input("price : "))
  		

  		
Conditional Statements: 
 if-elif-else(synatx)
 	
 	if(condition):
 		statement 1
 	elif(condition):
 		statement2
 	else:
 		statementN
  		

** Best practice**

  - simple instructions
  - one instruction per task
  - short and meaningful variable names
  - use appropriate Comments
  - avoid complex expressions


**Input in python**:
- input() statement is used to accept values from user
- input() #result for input() is always a str
- int (input()) #int
- float (input()) #float


**type conversion**: 
 - python does automatically
 - can be concatinate only same types

**Type casting**: 
 - we need to do manually
 - we use some functions here
 - can typecast float into string
 - works only when when other types contains data which fits into our new type

**Strings**

 - String is a data type that stores sequence of characters.
Basic operations:
  concatenation:
    "hello" + "world" ---> "helloworld"

  length of str
    len(str)

  escape sequence characters:
	\n
 	\t

    some topics realted to string: 
 		- indexing (postion of characters )
   		- slicing (accessing parts of a string)
      (note : we comsider -ve index only while slicing, noraml string index are always starts with zero to -ve side)


string Functions:
str.endswith("any ending word") #returns true value if string ends with substr
str.captalize()   #capatalizes 1st char
str.replace("old" , "new") #replaces all occurances of old
str.find("word") #returns 1st index of 1st occurrer
str.count("word to count")  #counts the occurrence of substr
  
 
 
