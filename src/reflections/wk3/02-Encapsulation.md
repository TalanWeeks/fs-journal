# Encapsulation

## What is the purpose of Encapsulation?

*  The purpose is to provide security of data. It means to keep data accessible to only files and functions that need to access them. It makes things safe from user manipulation.

## What were some of the problems with closures and the underscore prefix?

*  They cause variables to only be usable in their class that calls them or function that they are in. This can cause issues if you want to change these variables in a different section of code.

## How do we create private variables in a ES6 Class? Why would you do this?

* Private variables are declared using closures and underscore prefix. It makes manipulating the variable very hard to do. It also makes accessing it as a user almost impossible. This would be important for variables/ data such as passwords or socials. Only accessible by the object that owns it/ current class. not global.


https://talanweeks.github.io/fall21-gregslist-1/