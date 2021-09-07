# Promises in Javascript 

## What are the three states of a Promise?

* Pending: Initial state before the promise succeeds or fails
* Resolved: Completed Promise
* Rejected: Failed Promise

## How do promises seek to resolve the issues of "callback hell"?

*  Promises use then() and catch() to prevent data fall out of stuck states/ missed errors in your code. 

## What is the difference between .then() and .catch()?

* then() is only for resolved promises it doesn't read it if the promise failed. That is where catch() comes in. Catch() is used to do an action if the promise fails.