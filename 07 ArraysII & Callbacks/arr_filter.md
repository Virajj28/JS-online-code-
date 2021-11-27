
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

# return numbers.filter(function(number) {
#    return number >= 10;
});

# Don't forget the return keyword inside the callback function.

-------Program Code------

# Positive temperatures
Complete the function getPositiveTemperatures such that it returns an array containing the positive temperatures (the temperatures that are above 0).

# was missing return in first place.

function getPositiveTemperatures(temperatures) {
#   return temperatures.filter(function(temperature) {
#      return temperature > 0;
# });
}

-------Program Code------

# Freezing temperatures
Complete the function getFreezingTemperatures such that it returns an array containing the freezing temperatures (the temperatures that are below 0).

# One shot done!!!

function getFreezingTemperatures(temperatures) {
#   return temperatures.filter(function(temperature) {
#      return temperature < 0;
# });
}

