To convert a string to a number.

let str = "42";
 # Number.parseInt(str, 10); 
//42

The function name is called Number.parseInt(). Yes, including the Number. bit. This is because there's a global object called Number which contains a method called parseInt().

This Number.parseInt() method expects 2 parameters:

# Number.parseInt(string, radix);

Solve a problem code:(Get next age 1) to return age by 1 next year.

# export function getNextAge(age) {
# return Number.parseInt(age, 10) + 1;
# }

mistakes return Number.parseInt(age, 10) ;

-----------------------------------------

Solve a problem code Get box width:Complete the function getBoxWidth such it returns the width (as a number) from the string it receives.
Note that the string it receives looks like 50px or 100px (which is used in CSS) whereas the functions should return a number from these strings.

# Gr8 success!! Looks for his index file
export function getBoxWidth(value) {
return Number.parseInt(value);
}