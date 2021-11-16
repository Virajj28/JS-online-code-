
# Advanced If

You can drop else sometimes

# Legacy note
A quick legacy note. If you encounter == (double equal) in JavaScript, aim to replace it with === triple equal.
The double equal operator performs some conversions that you wouldn't expect. Always stick with triple equal instead.

# Always use triple equal === when comparing 2 values in JavaScript

-----Program Code------

# Get next age II

Complete the function getNextAge such that it returns the age next year (by adding 1 to the current age).
Note that the age is provided by the user in a text box (which you can try in the browser tab).
However, when the text box is empty, the function returns NaN. We need to fix that and make it show 0 instead of NaN.

--was tough abit--

export function getNextAge(age) {
if (age === ""){
    return 0;
}
return Number.parseInt(age, 10)+1
}



