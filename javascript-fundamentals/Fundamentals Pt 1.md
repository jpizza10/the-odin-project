# Learning outcomes

* How do you declare a variable in JS?
* What are three different ways to declare a variable in JS?
* Which one should you use and when?
* What are the rules for naming variables in JS?
* What are operators, operands, and operations?
* What is concatenation and what happens when you add number and string together?
* What are different types of operators in JS?
* What is the difference between == and === in JS?
* What are operator precedence values?
* What are the increment/decrement operators?
* What is the difference between pre-fixing and post-fixing them?
* What are assignment operators?
* What is the "Unary+" operator?

## Notes
### Numbers

Javascript contails only one type of number. All numbers stored as a double precision float which is 64 bits (0-63 is possible location of the bits) of information where:
  * Value: 52 bits (0-51)
  * Exponent: 11 bits (52-62)
  * Sign: 1 bit (63)
  
 #### Precision
 Maximum number of decimals is 17 and maximum number of values in an integer is 15.
 
 #### Operations
 
 If you add two numbers result will be a number. 
 If two strings are added the strings will be concatenated to a string.
 If you add a number and a string the result will be a string.
 
 Can perform other mathematic operations in javascript with numeric strings with no issues. 
 Issues when using "+" as it acts as concatenation operator whenever 1 string is involved.
 
 #### Special Cases
 
 Javascript can interpret hexadecimal as number if 0x notation is used.
 
 NaN = Not a Number 
 Infinity = the largest number that JS can operate on
 
 #### Numbers as objects
 
 Numbers can be objects and created in object creation procedure.
 
 var x = new Number(223);
 
 #### Operations
 
 Operator | Description
 ---------|------------
 \+ | Addition
 \- | Subtraction
 \/ | Division
 \* | Multiplication
 \** | Exponentation
 \% | Modulus operator
 \+\+ | Increment
 \-\- | Decrement
 
 ### Variables
 
 Variables are able to be declared using var, let, or const.
 
 ``` let message = "hello, world" ```
 
 There is a difference in the use of let and var in variable declarations.
 
 Variable names can not begin with a number and can only contain letters, numbers, underscores, or $.
 
 Some names are resereved and cannot be used as a variable name.
 
 To declare a immutable variable, instead of using 'let'. Use 'Const' i.e.
 
 ''' const currency = 93094.930 '''
 
 Can utilize constants with capital letters for hard-coded values that will not change at runtime.
 
 ''' const COLOR_GREEN = #F032 '''
 
 
 
 
 
 The assignment operator is =
