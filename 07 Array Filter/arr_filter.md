
# Array filter

.filter() method. When you call this method on an array, you will get back another array that contains some of the items from the original array, based on the condition you specify. 

let numbers = [9, 5, 14, 3, 11];

<!-- not recommended this -->
let numbersAboveTen = numbers.filter(function(number) {
    return number >= 10;
});
console.log(numbersAboveTen); // [14, 11]

<!-- Good approach -->
let numbers = [9, 5, 14, 3, 11];

# numbers.filter(function(number) {
#    return number >= 10;
});

# Don't forget the return keyword inside the callback function.