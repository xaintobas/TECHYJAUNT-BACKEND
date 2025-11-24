# Week 1 Assignment — TechyJaunt Backend Development

## Section A — Intro to Backend (Theory: 12 Questions)

**1. What is backend development and how is it different from frontend development?**  
Backend development is the process of creating the part of a website or app that the user does not see. It involves handling the logic, database, server, and API that make the app or website function properly.  
Frontend development is the process of creating the part of an app or website that the user interacts with, like images, buttons, and text.

**2. Mention three backend programming languages.**  
Python, PHP, JavaScript

**3. What is a server? Explain its role in backend development.**  
A server is a computer or system that receives requests from users and processes them to give back responses. It runs the backend code, handles the logic of a website or app, communicates with the database, and sends data to the frontend.

**4. Define an API and explain its purpose.**  
API (Application Programming Interface) is a means of communication between two or more software systems. It allows the frontend to request data from the backend.

**5. What is a database and why is it important in backend systems?**  
A database is a collection of information, such as users or payments. It is important because every backend system needs a way to store information.

**6. List two differences between SQL and NoSQL databases.**

- SQL uses table structure; NoSQL does not.
- SQL uses fixed schemas; NoSQL does not.

**7. What is a backend framework? Mention one example.**  
A backend framework is a tool built to help in creating backend apps or websites. Example: Express.js

**8. Explain what HTTP is and why it is important.**  
HTTP (Hypertext Transfer Protocol) defines a standard way to transfer files between the server and browser. It defines how information is requested and delivered on the internet.

**9. Mention two responsibilities of a backend developer.**

- Create APIs
- Manage the database of a website or app

**10. What does CRUD stand for? Explain each word.**

- **Create:** Insert new data into a database
- **Read:** Retrieve data from a database
- **Update:** Modify existing data in a database
- **Delete:** Remove information from a database

**11. What is authentication and why is it important for backend applications?**  
Authentication is the process of verifying a user’s identity. It protects user data from unauthorized access.

**12. What is the difference between a GET request and a POST request?**

- GET: Used to retrieve information
- POST: Used to submit information

---

## Section B — JavaScript Variables & Datatypes (Theory: 10 Questions)

**1. What is a variable in JavaScript?**  
A variable is a storage space where data can be stored. Example: storing a user’s name.

**2. List the three ways to declare variables in JavaScript.**  
`var`, `let`, `const`

**3. Explain the difference between let and const.**

- `let` allows updating the variable’s value
- `const` does not allow changing the value; it is constant

**4. Mention the seven primitive datatypes in JavaScript.**  
Boolean, String, Number, Null, Symbol, BigInt, Undefined

**5. What datatype is assigned to the value: true?**  
Boolean

**6. What datatype is a JavaScript array?**  
Object

**7. Give one example of a string in JavaScript.**

```javascript
let name = "Stephen";
```

**8. Give one example of a number in JavaScript**
An example of number in JavaScript is -

```javascript
let num = 12;
```

**9. What will be the output of this expression? `typeof "123"`**
The output will be String, because the `typeof` helps you get the data type and since the values are in quotes, it will return string.

**9. Explain the difference between null and undefined.**
Null is when a value is not set `(let name = null)` while undefined is when the value is not assigned to a variable `(let name;)` .

---

## Section C — Coding Questions (8 Questions)

**1. Declare a variable using let and assign your name to it.**
`let name = “Stephen”;`

**2. Write JavaScript code to add two numbers and log the result.**1.

```js
let num1 = 3;
let num2 = 5;
let sum = num1 + num2;
console.log(sum);
```

**3. Create an object called student with properties: name, age, and department.**

```js
let student = {name: “Stephen”, age: 10, department: “Backend Development”}
```

**4. Write a JavaScript function called greet() that prints "Hello World".**

```js
function greet() {
console.log(“Hello World”)
}
```

**5. Write a program that checks if a number is even or odd.**

```js
function checkEvenOdd(number) {
  if(number % 2 === 0) {
  console.log(“Number is even”);
  }else {
  console.log(“Number is odd”);
  }
}
```

**6. Create an array of 5 colors and print the first color.**

```js
const arrayOfColor = [“RED”, ”GREEN”, ”BLACK”, ”BLUE”, ”YELLOW”];
console.log(arrayOfColor[0]);
```

**7. Write a function that returns the square of a number passed into it.**

```js
function squareNumber(number) {
return number \* number;
}
```

**8. Write a small code snippet that converts a string to a number:**

```js
let value = "42";
let number = Number(value);
```
