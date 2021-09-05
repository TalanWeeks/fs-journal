# JS Proxy Objects

## What are the two common operations that we will set in the handler?

* A get operation and a set operation are the two typical operations used inside of handlers. The get operation is used to get data from typically objects using a key. Is two main parameters are the object itself and the property being accessed by it. The set operation is used to set data in the program. It takes in three parameters: the object, the property being accessed and the value being set for that property.

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

* The get operator must take in two parameters: the object itself, and the property being accessed. Get functions are always trying to return something back. If you don't give it something to return it will return undefined.

## What are some of the benefits of the proxy object that we are using in our structure for applications?

* The major benefits for proxy objects are the ability to have better control over data. They can be used to make sure objects and data are being used and accessed correctly and by the correct people.