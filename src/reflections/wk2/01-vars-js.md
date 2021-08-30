# Variables in JS

## What is Scope ?

* Scope essentially means where these variables are available for use. It can be either locally or globally. If a var is declared outside of the function is is global, if its inside the function its locally set.

## What is Hoisting ?

* Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. The code runs 2 times the first is to define things throughout the code so that it can be used the second time around and have values set to it. If the code didn't do this then it wouldn't run functions that are called before they are defined

## In what cases might you use let vs const vs var?

* Var declarations are globally scoped or function scoped while let and const are block scoped. Var variables can be updated and re-declared within its scope. Let variables can be updated but not re-declared.Const variables can neither be updated nor re-declared.

*  https://talanweeks.github.io/js-tests-basics/