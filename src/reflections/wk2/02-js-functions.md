# JavaScript functions

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

* 1. A Function Declaration defines a named function. To create a function declaration you use the function keyword followed by the name of the function. ex: "function name(parameters) {statements}"

* 2. A Function Expressions defines a named or anonymous function. An anonymous function is a function that has no name. Function Expressions are not hoisted, and therefore cannot be used before they are defined. ex: "let name = function(parameters) {statements}"

* 3. An Arrow Function Expression is a shorter syntax for writing function expressions. Arrow functions do not create their own this value. ex: "let name = (parameters) => {statements}"


## What is the difference between Parameters and Arguments?

* Parameters are used when defining a function, they are the names created in the function definition. Arguments, on the other hand, are the values the function receives from each parameter when the function is executed (invoked).

## What are higher order functions? Can you provide an example?

* When a function accepts another function as a parameter, or returns a function, it is called a higher-order function. ex: Array.prototype.map, Array.prototype.filters

* https://talanweeks.github.io/js-tests-loops-and-arrays/