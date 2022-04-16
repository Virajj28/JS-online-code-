
# Conditions

if , else if 

 A note regarding ligatures: === that you're seeing is in fact 3 equal signs after each other ===
The fact that they show up as a single character is a feature that you can enable in your code editor, it's called a ligature and is supported by some fonts.

# Can you vote?

Implement the function canVote such that it returns true whenever the age 18 or above and false in all other scenarios.

# Gr8 success on one go not for real

<!-- function canVote(age) {
if (age>=18){
    return true;
}
else return false;
} -->

For sake of for loop and ternary above solution was perfect but actual solution is:
function canVote(age) {
 return age >= 18;
}

// Sample usage - do not modify
console.log(canVote(25)); // true
console.log(canVote(18)); // true
console.log(canVote(10)); // false
