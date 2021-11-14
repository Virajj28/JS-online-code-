To convert a string to a number.

let str = "42";
 # Number.parseInt(str, 10); 
//42

The function name is called Number.parseInt(). Yes, including the Number. bit. This is because there's a global object called Number which contains a method called parseInt().

This Number.parseInt() method expects 2 parameters:

# Number.parseInt(string, radix);

Solve a problem code: to return age by 1 next year.

# export function getNextAge(age) {
# return Number.parseInt(age, 10) + 1;
# }

mistakes return Number.parseInt(age, 10) ;