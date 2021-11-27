
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

-----Program Code-------
# Classroom Project I
This is a classroom project! You can enter grades in the browser tab and add them to the app, which will show you various statistics about the classroom. For example, you will see the average grade, all the failing grades, etc.

Each function has a comment describing what it should return, but you can also find them below:

getNumberOfGrades should return the number of grades.
getSumGrades should return the sum of all the grades.
getAverageValue should return the average value of all grades (sum of all grades divided by the total number of grades).
getPassingGrades should return all passing grades (10 and above).
getFailingGrades should return all failing grades (9 and below).
getRaisedGrades should return all the grades raised by 1 (grades should not exceed 20).

# Checks to be passed

export function getNumberOfGrades(grades) {
    // TODO: return the number of grades
# return grades.length
}

export function getSumGrades(grades) {
    // TODO: return the sum of all the grades
   let sum = 0;
   grades.forEach(function(grade){
       sum+=grade;
   })
   return sum;
}

# best fav method
export function getAverageValue(grades) {
    // TODO: return the average value of all grades (sum of all grades divided by the total number of grades)
return getSumGrades(grades)/grades.length;
}

# big mistake was using find
export function getPassingGrades(grades) {
    // TODO: return all passing grades (10 and above)
   return grades.filter(function(grade){
       return grade>=10;
   })
}

export function getFailingGrades(grades) {
    // TODO: return all failing grades (9 and below)
return grades.filter(function(grade){
    return grade<=9;
})
}

export function getRaisedGrades(grades) {
    // TODO: return all the grades raised by 1 (no grade should exceed 20)
return grades.map(function(grade){
    if(grade+1 > 20){
        return 20;
    }
    else 
    return grade+1;
})
}
