# Day 48
__02/24/2020__

## Thoughts on Dotnet WebAPI SQL Injection

### What is SQL injection?
A cyber attack perpetrated by inputting arbitrary SQL code into a database query. One of the simplest ways to do so is via user input fields.

### What are 3 methods SQL injection can be done by?
One is inputting SQL statements into user input fields. Alternatively, cookies can be modified to deliver SQL injection or server variables like HTTP headers.

### How can we detect and sanitize SQL injection attacks?
A web application firewall can detect and block basic SQL injection attacks. One method of prevention is handled by limiting account priviledges.

#### Afternoon Lab: [C# Auth0](https://github.com/trevor-r-allen/csharp-auth0-taskmaster)