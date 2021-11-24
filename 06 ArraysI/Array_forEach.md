
## Imp Concept go through revise before starting.

# Array forEach

Array iteration is one of the most important concept that you will use in JS.

# Always start with a console.log() inside your .forEach()  so that you can visualize the shift from array to array item.

-----A good story line-----

The .forEach(callback) method allows you to run the callback function for every item in that array. Callbacks will be explained in more depth in the follw. chp.

# For now let's start w/ a basic defn.
A callback is a function that is passed to another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

function(grade) {
    <!-- do something with individual grade -->
  console.log(grade);
}

This callback function receives a grade and then logs it to the console. This is a function definition because it's not being executed. It only defines the behavior of the function. However, this function definition is passed as an argument to the .forEach() method

# grades.forEach(insert_callback_here);

Once you combine the two together, as in, pass the function definition as an argument to the .forEach() method, then you get:

# grades.forEach(function(grade){
    <!-- do something with Individual grade -->
#    console.log(grade);
# });

# And then this code will log every grade from grades array.

Visualise as this :

<!-- this is a callback -->
function (grade) {
    console.log(grade);
}
<!-- CALL the callback with grade=10 -->
console.log(grade); //will log 10
<!-- CALL the callback with grade=8 -->
console.log(grade); //will log 8
<!-- CALL the callback with grade=13 -->
console.log(grade); //will log 13

Notice how the function definition is being called for every item in the array!

But who's calling it and providing the different values? Well, JavaScript is! You provide the callback (function definition) and pass it to the .forEach() and JavaScript does the rest!


# Recap for best results :

1+> .forEach(callback) iterates over every item in an array.
2+> A callback is a function definition passed as an argument to another function.
3+> Always start with a console.log() inside the .forEach() to visualize the shift from array to array item (you can skip that when you become used to it).
4+> The .forEach() method will take your function definition and call it for every item of the array. Every time it calls it, it will replace the first parameter with the corresponding array item.