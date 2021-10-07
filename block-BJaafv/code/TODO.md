1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
ans. Here in first case return always return the value in arrow format but console.log always logs the value it ill pass the undefined and this is the main difference between both of these functions.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
ans. Value of first will be the sum but for second  value will be undefined.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
ans. It will do the saame work just the difference is that 35 will get ignored by sum.


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
ans. Yes we can store a function in a variable.  because function is an expression.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
 function sayHello(name){
   let name = 'Arya';
   return `Hello ${name}`;
 }
 
```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
//'Hello, John'


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // 'Hello, John'

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.
ans. 
Function without name is anonymous function.
```js
let sum = function (a, b) {
  return a + b;
};

let pow = (a, b) => {
  return a ** b;
};

let sayHello = (name) => `Hello ${name}`;
```

9. Can function declaration be a Anonymous Function? Explain.
ans. No, a function declaration cannot  be a Anonymous Function because in function declaration  to declare aa function we need a name while on other hand in anonymous function we provide a variable name to the  function but the for both of function is same. 

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
 1-getName
 2-calcSum
 3-createSentence
 4-checkAge