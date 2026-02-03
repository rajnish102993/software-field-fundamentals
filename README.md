Software Field Fundamentals

QUESTION 1
What is a Variable?

Answer:
A variable is used to store data in memory so your program can use it again and again.
Without variables, programs cannot remember anything.

Real Use:
- Storing user name
- Age
- Price
- API response

Example:
```php
$userName = "Raj";

```
========================================

QUESTION 2
Difference between == and ===?

Answer:
== compares only value.
=== compares value and data type.

Real Use:
Avoiding bugs in conditions.

Example:

"5" == 5    // true
"5" === 5   // false
========================================

QUESTION 3
What is a Function?

Answer:
A function is a reusable block of code that performs one specific task.

Real Use:

Login logic

Calculations

API calls

Example:

function add($a, $b) {
  return $a + $b;
}
