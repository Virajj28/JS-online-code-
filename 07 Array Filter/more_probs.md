
# Is app used?
Complete the function isAppUsed such that it returns true when the app parameter it receives exists in the apps parameter, and false otherwise.

# Easy good one

function isAppUsed(app, apps) {
  // Your code here
  return apps.includes(app);
    false;
}

------Program Code-------
# String Sizes
Complete the function getStringSizes such that it returns an array of the number of characters for every string it receives in the strings parameter.

This means, for the array ["abc", "d"] it should return [3, 1] that's because the first string is made up of 3 characters and the second string is made up of 1 character.

# Just cuz I forgot to return keyword in first line

funtion getStringSizes(strings) {
#  return strings.map(function(string) {
#   return string.length;
  });
}