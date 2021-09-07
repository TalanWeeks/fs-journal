# CallBacks hell and how to avoid it

## What are some of the signs and causes of Callback Hell?

* Nesting functions is a prime way to cause callback hell. Basically not doing any of the 3 things to fix callback hell will create it. Not keeping code shallow, having functions do a ton of different stuff.

## What does the asynchronous mean and how are callbacks involved?

* Asynchronous means not synched or out of sync. CallBacks are highly involved because they are used to handle Asynchronous code. They run the code and will process the data, but they send the data to another function called the callback function. This functions job is to display the data or result of the function calling it once the process is complete.

## Summarize the 3 ways to avoid / fix Callback Hell

*  1 keep your code shallow- keeping functions as short and independent as possible. "one function for one job" if possible...
*  2 Modularize- This is like keeping functions doing one task but on the other level of whole files. These files should do specific things and handle specific data.
*  3 Handle every single error- Try to predict errors happening almost anywhere. use try and catch to try and function then catch whatever error is thrown so you can present it to the screen.