
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

Even though the variable numbers was defined with const, we were able to push new data into it.
That's because const means you can only assign the variable once when it's defined. But it doesn't mean the variable is immutable. Its content can change.

What's the benefit of declaring it as a const you ask? The benefit is that once you define it as an array, it will always stay as an array which means you can safely call array methods on it. However, the array content can change.

eg. const numbers = []; // start with empty array
    numbers.push(10); // returns 1 (new length of array)
    console.log(numbers); // [10] (still an array but content changed)
    numbers.push(20); // returns 2 (new length of array)
    console.log(numbers); // [10, 20] (still an array but content changed)


    --------Program Code--------
    # Empty array

    --------Program Code--------
# Number of elements

    --------Program Code--------

Add calci to apps


  #  use any app