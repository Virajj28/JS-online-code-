
## Arrays

Arrays in JavaScript allow you to store multiple elements in the same variable. You can store numbers, strings, booleans, arrays, objects & more. These can be mixed within the same array.

# Name arrays in the plural as they can contain more than one item. This will prove to be especially useful once we need to iterate over an array.

# .length property

You can get the no. of elements in an array using the .length property.

# Get element by index

~ly using strings, you can get the element from an array by using [] square brackets syntax with index starting from 0.

eg. const users = ["shaun", "crystal", "ryu"];
    users[1]; // crystal

# Adding an element

You can add an element to an array by using the .push() method. Array.push() return the new length of the array.

eg. const number = [10, 8 ,13, 15];
    number.push(12); // retunrs the new length of the array
    console.log(number); // [10, 8, 13, 15, 12]
