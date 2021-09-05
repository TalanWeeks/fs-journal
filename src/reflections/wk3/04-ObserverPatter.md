# The Observer Pattern

## What problems does the Observer Pattern seek to solve?

* It seeks to solve the problem of trying to keep a bunch of elements tied and synced with the same data. This tied with ES6 should allow you to create a very functional app that doesn't break when having multiple functions on elements.

## What are the three mechanisms of the observer pattern?

* The three main mechanisms of the observer patter are: subscribe- adds new observable events, unsubscribed- removes observable events, and broadcast- executes all events with bound data.

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

* In the bcw-template the ProxyState is observed a ton to see if certain data peices in it  change. For instance, if a certain array in the ProxyState like Tasks:[] is updated you want the screen to update the html to represent whatever change has occured. This is done by watching the state with a certain key passed in. In the example above the key that was passed in would be the Tasks array.