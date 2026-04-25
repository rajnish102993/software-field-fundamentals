# 📘 Software Field Fundamentals

Basic software development concepts explained in simple and clear language.

---

## ✅ 1. What is a Variable?

### 📖 Answer:
A **variable** is used to store data in memory so your program can reuse it later.  
Without variables, programs cannot remember information.

### 💡 Real-World Uses:
- Storing a user's name  
- Storing age  
- Storing price  
- Saving API responses  

### 🧑‍💻 Example (PHP):
```php
$userName = "Raj";
```

---

## ✅ 2. What is the Difference Between `==` and `===`?

### 📖 Answer:
- `==` compares **only values**.
- `===` compares **both value and data type**.

### 💡 Why It Matters:
Using `===` helps avoid unexpected bugs caused by type conversion.

### 🧑‍💻 Example:
```php
"5" == 5    // true
"5" === 5   // false
```

---

## ✅ 3. What is a Function?

### 📖 Answer:
A **function** is a reusable block of code that performs a specific task.

### 💡 Real-World Uses:
- Login logic  
- Calculations  
- API calls  

### 🧑‍💻 Example:
```php
function add($a, $b) {
  return $a + $b;
}
```

---

## ✅ 4. What is the Difference Between `null` and `undefined`? (JavaScript)

### 📖 Answer:
- `undefined` means a variable is declared but not assigned a value.
- `null` means the variable is intentionally empty.

### 🧑‍💻 Example:
```javascript
let a;
console.log(a); // undefined

let b = null;
console.log(b); // null
```

---

## ✅ 5. What is the Difference Between GET and POST?

### 📖 Answer:
- **GET** is used to retrieve data from a server.
- **POST** is used to send data to a server.

### 💡 Key Differences:
- GET data is visible in the URL.
- POST data is sent inside the request body.
- GET is generally used for fetching data.
- POST is generally used for creating or submitting data.

---

## ✅ 6. What is Scope?

### 📖 Answer:
Scope defines where a variable can be accessed in your program.

### 📌 Types:
- Global Scope  
- Local Scope  
- Block Scope  

### 🧑‍💻 Example:
```javascript
let name = "Raj"; // Global scope

function test() {
  let age = 25; // Local scope
}
```

---


## ✅ 7. What is the Difference Between `let`, `var`, and `const`? (JavaScript)

### 📖 Answer:
- `var` → Function-scoped (old method)
- `let` → Block-scoped
- `const` → Block-scoped and cannot be reassigned

### 🧠 Tip:
In modern JavaScript, prefer `let` and `const`.

---


## ✅ 8. What is the difference between Session and Cookie in PHP?

### 📖 Answer:

- `Session` → Stored on the server.

- `Cookie` → Stored in the browser.

- Sessions are generally more secure because data is not stored on the client side.

💡 Real-World Uses:

Login systems

Remember me functionality

Storing user preferences

### 🧑‍💻 Example (PHP Session):
```
$_SESSION['user'] = "Raj";
```




## ✅ 9. What Does npm run dev Mean?

### 📖 Answer:

npm run dev is a command used in JavaScript projects to start a development server.

It has three parts:

npm → Node Package Manager

run → Tells npm to run a script

dev → The name of the script defined in package.json

🔎 Breakdown:
1️⃣ What is npm?

npm (Node Package Manager) is a tool that comes with Node.js.
It is used to:

Install packages

Manage dependencies

Run project scripts

Example:

```
npm install
```
2️⃣ What is run?

run tells npm to execute a script inside the package.json file.

3️⃣ What is dev?

dev is usually a development script name.

Example inside package.json:

```
{
  "scripts": {
    "dev": "vite",
    "build": "webpack",
    "start": "node server.js"
  }
}
```

Running:

npm run dev

Actually runs:

vite
💡 Why Use dev?

It usually:

Starts a local development server

Enables hot reload

Shows detailed errors



## ✅ 10. What is an API?
### 📖 Answer:

An API (Application Programming Interface) allows two different software systems to communicate with each other.

It acts like a bridge between applications.

💡 Real-World Uses:

Fetching weather data

Login with Google

Payment gateways

Mobile app ↔ server communication

🧑‍💻 Example (JavaScript Fetch API):
fetch("https://api.example.com/users")
  .then(response => response.json())
  .then(data => console.log(data));

Here your program is requesting data from another server using an API.

## ✅ 11. What is Debugging?
### 📖 Answer:

Debugging is the process of finding and fixing errors (bugs) in a program.

Every developer spends a large amount of time debugging.

💡 Common Debugging Methods:

Using console.log()

Checking error messages

Using browser developer tools

Using breakpoints

🧑‍💻 Example:

```
let price = 100;
let total = price * quantity;

console.log(total);

```

If quantity is not defined, debugging helps identify the issue.

🧠 Tip:

A good developer is not the one who writes code fastest,
but the one who can debug problems efficiently.



## ✅ 12. What is CSRF Protection in Laravel?
### 📖 Answer:
CSRF (Cross-Site Request Forgery) protection ensures that unauthorized users cannot perform actions on behalf of authenticated users.

Laravel automatically protects your application from CSRF attacks by generating a unique token for each user session.

📌 Important Point (often ignored):
Every form must include a CSRF token, otherwise the request will be rejected.

```
🧑‍💻 Example:

<form method="POST" action="/submit">
    @csrf
    <input type="text" name="name">
    <button type="submit">Submit</button>
</form>

```




# 🚀 Why This Repository?

Many developers skip these simple fundamentals.  
Strong basics = Strong developer.


---



