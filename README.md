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

# 🚀 Why This Repository?

Many developers skip these simple fundamentals.  
Strong basics = Strong developer.


---


