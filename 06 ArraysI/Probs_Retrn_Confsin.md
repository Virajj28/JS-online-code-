
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

----------------------------------------------------

# Countries dropdown I
Complete the function getDropdown such that it returns the following HTML that will fill the existing <select></select> element. The HTML that's returned should look like the following:

It should start with: <option value="">Please select</option>
Then, for every country you should have the <option> for that. For example, for the country "Netherlands", you should have the following <option value="netherlands">Netherlands</option>
Notice how the value contains the country name in lower case. The remaining countries will need to show up as well following the same criteria.

# Damn tough logic dude.

export function getDropdown (countries) {
#  let dropdown = '<option value="">Please select<option>';
#  countries.forEach(function(country) {
 #   dropdown += `<option value="${country.toLowerCase()}">${country}</option>`;
 # });
  # return dropdown;
}


----------------------------------------------------

# Nutrition table II
Complete the function renderTableRows such that it returns the following HTML:

<tr>
    <td>label here</td>
    <td>value here</td>
</tr>
for every row that it receives in its rows parameter.

The rows parameters looks like the following:

[["Carbs", "17g"], ["Protein", "19g"], ["Fat", "5g"]]
This is a nested array. Every inner array contains 2 items, the first one referring to the label that you should replace instead of label here and the second one referring to the value which you should replace instead of value here.
Make sure to use console.log() every step of the way to visualize what you're working with.

# Logic is a bit tricky. Can be solved no look for back prob.

export function renderTableRows (rows) {
  # let html = '';
  # rows.forEach(function(row) {
  #  html+= `
  #   <tr>
  #    <td>${row[0]}</td>
  #    <td>${row[1]}</td>
  #  </tr>`
  })
 # return html;
}