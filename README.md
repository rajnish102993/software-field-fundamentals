# Software Field Fundamentals 

## 1. What is a Variable?

A variable is used to store data in memory so your program can use it again and again.
Without variables, programs cannot remember anything.

### Real Use
storing user name, age, price, API response, etc.

### Example
```php
$userName = "Raj";

Now you can use $userName anywhere.

2. Difference between == and ===?

== compares only value, === compares value + data type.

 Real use: 
avoiding bugs in conditions.

Example (PHP/JS):

"5" == 5   // true
"5" === 5  // false


3. What is a function?

A function is a reusable block of code that performs one task.

Real use: login logic, calculations, API calls.

Example:
function add($a, $b) {
  return $a + $b;
}

