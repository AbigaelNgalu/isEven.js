# isEven.js
📘 isEven.js
This JavaScript file defines a utility function called isEven that checks whether a given number is even.
🧠 Function Overview
function isEven(num) {
  if (num % 2 === 0)
    return true;
}


- Input: A number (num)
- Output: Returns true if the number is even; otherwise returns undefined
⚠️ Note: The function does not explicitly return false for odd numbers. You may want to update it for completeness.

✅ Example Usage
console.log(isEven(4)); // true
console.log(isEven(7)); // undefined (expected: false)
console.log(isEven(2)); // true


🛠 Suggested Improvement
To make the function more robust, consider adding an else clause:
function isEven(num) {
  return num % 2 === 0;
}


Or:
function isEven(num) {
  if (num % 2 === 0) {
    return true;
  } else {
    return false;
  }
}



