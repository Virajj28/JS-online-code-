
# Even & Odd 

Notice how the division remainder by two is always 0 when the number is even. Whereas it's 1 when the number is odd.

------Program Code------
# Get division remainder by 2

Complete the function evenOrOdd such that it returns the string "even" when the number parameter it receives is even and "odd" otherwise.
Can you make it work with negative numbers too?

# A bit tricky but solved

export function evenOrOdd(number) {
if (number%2)
{
    return ("odd");
}
else return ('even');
}