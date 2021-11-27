
The array .map(callback) method allows you to transform an array into another one.
The array .includes(item) method takes an item and returns true when that item exists in the array and false otherwise.
The array .join(glue) method returns a string of the array elements separated by the glue.

// How .map code
const numbers = [4, 2, 5, 8];

const doubled = numbers.map(function(number) {
    return number * 2;
});
console.log(doubled); // [8, 4, 10, 16]

# another example
const names = ["sam", "Alex"];
names.map(function(name) {
    return name.toUpperCase();
});

// How .includes code
const groceries = ["Apple", "Peach", "Tomato"];

groceries.includes("Tomato"); // true
groceries.includes("Bread"); // false

// How .join code

const groceries = ["Apple", "Peach", "Tomato"];
groceries.toString(); // "Apple,Peach,Tomato"

# Another example
const groceries = ["Apple", "Peach", "Tomato"];
groceries.join("; "); // "Apple; Peach; Tomato"
groceries.join(" . "); // "Apple . Peach . Tomato

