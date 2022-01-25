1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function (marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

let percentage = (marks, total) => (marks * 100);

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// function declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
function expression
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
function expression
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
function expression
```js
let percentage = (marks, total) => (marks * 100) / total;
```
function expression

```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
```js
function is an object and object is value thats why fuction is an expression in javascript.

function add(){

}
let obj = {};
let add = function(){}
```
4. Why is function call an expression in javascript?
ans function call always return a value thats why function call an expression in javascript.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid 5
five = add; // valid
five = five(10, 11); // valid 21
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
``` function defination when you define a function.

function add(){ 
} //defination 
```function call when you call a function by parenthesis.
add();

7. What is the similarities between function definition and function call?
```js
 function defination is an expression because function is an object.function call is an expression because it always return a value.
 ```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
```js
// - That accepts a function defination 
// - that return a function defination 

function add(cb){ // HOF
cb()
}
function add(){ // HOF
function main(){}
return main 
}
```

10. Explain what is callback function. Why you can pass a function inside a function?
```js 
// because function is an expression in js we can pass a function inside another function.
//