# Array Find

 .find(callback) method will call the callback that you provided for every item in the array until one of the callbacks returns true. When this happens, it will stop calling the remaining callbacks and return to you the item for which the callback returned true.

 # .filter() vs .find()
So, what is the difference between .filter() and .find()?

The difference has to do with the return type of these 2 methods:

The .filter() method always returns an array.
The .find() method returns the first array item that matches the callback function or undefined.

# .filter() always returns an array. Even if it matched one item or no items.
# .find() returns the first array item that matches the callback function or undefined.

--------Program Code --------
# Get year
Complete the function getYear such that it returns the searchYear (passed as 2nd parameter) when it's found in the array. Otherwise, it should return undefined.

# sometimes I make it tricky.

function getYear(years, searchYear) {
# return years.find(function(year){
#    return year === searchYear;
})
}

------Program Code-------
# Odd years 

Complete the function getOddYears such that it returns all the years that are odd from the years parameter it receives.

# was using find my bad used to filter.

function getOddYears(years) {
# return years.filter(function(year){
#    return year % 2 !== 0;  //other approach can be
#    return year % 2;        //best approach to remember for me
})
}


