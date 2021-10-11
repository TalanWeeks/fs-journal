# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file tells you what dependencies you have on your app and  what versions they are.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
You want it on the top most level of your files so that it is accessable to all of your files that need to refer to it
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Heroku / PaaS (Platform as a Service)
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
heroku logs -n 1500, heroku logs -t 
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Set remote for your project then push to heroku master to deploy the upgrades/changes to the app
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching lets you change a ton of stuff on the app but also keeps its original if you wanted to go back to it or set data back to default
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code reviews should happen after all the code has been written and tested
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging 
```
