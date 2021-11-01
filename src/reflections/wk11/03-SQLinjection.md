# SQL injection usage

## What is SQL injection?

* SQL injection is a type of attack that can give an adversary complete control over your web application database by inserting arbitrary SQL code into a database query. This is the number one attack/vulnerability of the web applications.


## What are 3 methods SQL injection can be done by?

* The simplest form of SQL injection is through user input (direct insert), also modify cookies to poison a web application's database query (modifying cookies), Forged headers containing arbitrary SQL can inject that code into the database if the web application fails to sanitize those inputs as well and modifying http headers.

## How can we detect and sanitize SQL injection attacks?

*  Both network- and host-based, can be tuned to detect SQL injection attacks. Network-based IDSes can monitor all connections to your database server, and flag suspicious activity. A host-based IDS can monitor web server logs and alert when something strange happens.

https://talanweeks.github.io/vacaybackend/