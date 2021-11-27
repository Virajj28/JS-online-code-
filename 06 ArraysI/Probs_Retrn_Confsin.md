
# Sum grades
Complete the function sumGrades such that it returns the sum of all the grades it receives as a parameter. We haven't seen reduce yet, so try to solve it using what you have learned so far

# logic same but implementation left behind.

<!-- function sumGrades(grades) {
  return grades.reduce((acc, curr) => acc + curr, 0);
} -->

function sumGrades(grades) {
# let sum = 0;    
# grades.forEach(function(grade) {
# sum += grade;
});
# return sum;
}

# Sum of positive numbers.
Complete the function sumPositiveNumbers such that it returns the sum of all positive numbers from the numbers parameter it receives.

This challenge will help you combine some of the knowledge you acquired in this course. Take your time and make as many mistakes as possible!

# if else loop to be implemented.

function sumPositiveNumbers(numbers) {
  let sum = 0;
  numbers.forEach(function(number) {
    if (number > 0) {
      sum += number;
    }
  });
  return sum;
}

# Sum odd numbers
Complete the function sumOddNumbers such that it returns the sum of all the odd numbers from the numbers parameter it receives.
The function should also work for negative numbers.

# Be better at logic

function sumOddNumbers(numbers){
  let sum =0;
  numbers.forEach(function(number){
    if (number % 2 !== 0) {
      sum += number;
    }
  });
}


