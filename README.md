# Quiz 4

## Question 6

The two correct ansewrs to this question are 
function sayHi() {
    document.getElementById("my-paragraph").innerHTML = "Hi, there!";
} 
and 
function sayHi() {
    let p = document.getElementById("my-paragraph");
    p.innerHTML = "Hi, there!";
}
This is because they both change the innerHTML of an element to say Hi there! In addition, they both have the function name Hi there() so they can be correctly referenced in the HTML.

## Question 7

"" is also considered a falsey because it is an empty string. meaning there is no value, so it is automatically set to false.

## Question 8

The types of data points in javascript are object number null string symbol boolean and undefined.

## Question 10

The correct answer is
let x;
x = 27;
This is because, let x declares the variable x, and x=27 sets x to be equal to 27.

# Quiz 5

## Question 5

The '=' is also a valid relational operator because it compares two values.

## Question 7

let status = (studentGrade < 88) ? "ND" : "HR"; is also a correct answer. This is because, this is a ternary expression, and when evaluated to true studentGrade<88 , it will assign a value of ND to status, and HR to status, if evaluated to false studentGrade>88.

## Question 9

if (a < b)
{
    // do something
}

if (a < b) {
    // do something
}
These are the correct syntax for if statements. The syntax for if statements follow this
if(condition){
    //do something
}

## Question 13

The correct answer is 
for (let i = 0; i < 5; i++) {
    console.log(i);
}
Once i becomes greater than 5 it will terminate and for everytime the loop repeats while i < 5 one will be added to the value of i which starts at 0.

# Quiz 6

## Question 4

Prompt will return a user inputted value back to where it was called.

## Question 6

function divide(a, b) {
    return a / b;
}
is the correct answer. The parameters are a and b, and they are being divided in the function. If the values of a and b were modified in the function, then they would return as undefined due to the parameter list.

## Question 9

Both functions will run infinitely
In the first code, the functions will continue to reference each other indefinitely. The function do this() references do that() and vice versa indefinitely. In the second function, the condition for the if statement is if(i > 0) i already starts at 1, and the function updates i by adding 1, meaning i will always be greater than 0, and therefore the function will run indefinitely.

## Question 11

The correct answer is 4 or undefined will be printed to the console. this is because var d is not part of the parameter list, however, because var is being used to declare d as a variable, it is pushed to the top of the page.

# Quiz 7

## Question 8

The correct answer is the array [ -9, -1, -8, -2, -7, -3, -6, -4, -5 ]. This is because this array has negative numbers.