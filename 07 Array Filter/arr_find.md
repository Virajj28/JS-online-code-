# Array Find

 .find(callback) method will call the callback that you provided for every item in the array until one of the callbacks returns true. When this happens, it will stop calling the remaining callbacks and return to you the item for which the callback returned true.

 # .filter() vs .find()
So, what is the difference between .filter() and .find()?

The difference has to do with the return type of these 2 methods:

The .filter() method always returns an array.
The .find() method returns the first array item that matches the callback function or undefined.

# .filter() always returns an array. Even if it matched one item or no items.

