
# Operations

# ---Division remainder---
You can also use the remainder operator % which returns the division remainder. Here's an example:

8 % 2; // Division remainder is 0
7 % 2; // Division remainder is 1 

8 / 2 = 4
4 / 2 = 2
=> division remainder is 0 because 8 = 4 * 2 + 0

Where as for 7 % 2:

7 / 2 = 3 (rounded)
=> division remainder is 1 because 7 = 3 * 2 + 1

# Number methods
While there are some other methods you could call on numbers, they are not very commonly used. What is commonly used, however, is the Math object which contains methods such as min(), max(), round(), etc. 

---------Problem Code---------
# Get division remainder by 2
Complete the function getDivisionRemainderBy2 such that it returns the division remainder of the number it receives by 2. This means that it should return the division remainder by 2.
This challenge will further be developed into a small app that shows whether the number is even or odd in a future chapter.

# Gr8 success
export function getDivisionRemainderBy2(number) {
  // Write your code here
 return number % 2;
}
