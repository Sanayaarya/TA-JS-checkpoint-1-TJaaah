1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
 Ans.. In this function we are  returning a+b .

// second
function sum(a, b) {
  console.log(a + b);
}
```

Ans...  In this function we are console.log a+b .

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Ans.. function sum(a, b) {
  return a + b;
}
 let ans=sum(3,5)

ans
8


function sum(a, b) {
  console.log(a + b);
}
undefined
let ans = sum(23,33)
56
undefined
because we did'nt return any thing

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

Ans.. function sum(number){
      return number
      }
      sum(12,24,35)
 
 we give 1 or more then number to call but always take first two number to concate .

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

 Ans... Yes because we use expression function.


5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello(name){
  return name  
}
 sayHello("Hello Arya")

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
Ans..First we take one variable and take value and we make with the help of function case and result will come      'Hello,john' we take a variable name message and concate them and return message.

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); /* Output 1 */ Ans john

showMessage(); /* Output 2 */ Ans 'Hello, John'

alert(userName); /* Output 3 */ Ans  john
```

8. What is a Anonymous Function give example of three functions.

Ans.. An anonymous function is a function that was declared without any named identifier to refer to it.

let addNumber = function(numA,numB){
 return numA + numB ;
};

let addName = function(firstName ,lastName){
 return firstName + lastName ;
};

9. Can function declaration be a Anonymous Function? Explain

Ans.. No because it is decleration function not use of anonymous function.

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
Ans- function showMessage(message) {
     return message;
     }



function sum(a, b) {
  return a + b;
}

function creating(numA , numB){
  return numA + numB
}

function checking(number){
switch (true){
    case number==1||number==3||number==5||number==7||number==8||number==10||number==12:
return 31
break;
    case number==4||number==6||number==9||number==11:
return 30
break;
case number==2:
return  28
break;

    default:
return invalid;
}}

