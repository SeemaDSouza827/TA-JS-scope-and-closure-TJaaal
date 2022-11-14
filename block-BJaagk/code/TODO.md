1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// 
let percentage =(marks,total)=>{
  return (marks * 100) / total; 
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
//  Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
//Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
//Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
//Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
//Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
a function is an obeject in javaScript therfore function definition an expression in JavaScript
let percentage = (marks, total) => (marks * 100) / total;
4. Why is a function call an expression in JavaScript?
because it is an object 
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid
five = add; //Invalid
five = five(10, 11); //Invalid
five = function () {
  return 'Hello';
}; // Invalid
```

6. What is the difference between function definition and function call? Explain with an example.
function defination is defining the set of steps to be follwed to execute a perticular task
and function call is invoking the function by passing parmeters
function percentage(marks, total) {
  return (marks * 100) / total;
};
percentage(556,800);

7. What is the similarities between function definition and function call?
function defination is defining the set of steps to be follwed to execute a perticular task
and function call is invoking the function by passing parmeters
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // Invalid
```

9. What is higher order function explain with an example.
//Functions that takes other functions as an argument is called a higher order functions.

10. Explain what is callback function. Why you can pass a function inside a function?
a callBack function is used to invoke a pre defined function  by passing differnt paramets.
javascript acepts higher order function so we can pass a function inside a function.