To convert a string to a number.

let str = "42";
 # Number.parseInt(str, 10); 
//42

The function name is called Number.parseInt(). Yes, including the Number. bit. This is because there's a global object called Number which contains a method called parseInt().

This Number.parseInt() method expects 2 parameters:

# Number.parseInt(string, radix);