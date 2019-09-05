# How to avoid SQL Injection by using Prepared Statements with Dynamic Table Names
Java Prepared Statements are a good and easy way to avoid SQL Injection when performing SQL database operations in Java code.
However, in the case where you want to specify the table name to query or interact with based on outside input, it can be difficult to use Prepared Statements to avoid SQL injection.

# Why use Prepared Statements in the first place?
SQL Injection is a highly dangerous form of injection where an attacker can manipulate arbitrary data within a database. It is incredibly important to guard your web applications from this attack. When a user needs to retrieve data from the database, the Java code that interprets the HTTPrequest into a database query should be a layer of defense against injection attacks.

example of prepared statements

# Dynamic Table Names

example of dynamic table names
  
# Why it is vulnerable

# Solution
