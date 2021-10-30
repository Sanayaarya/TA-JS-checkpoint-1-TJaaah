1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
let sum = 0;
for ( let i = 0 ; i < 10 ; i++){
  let num = +prompt("enter any number");
      sum += num;
}
    let avg = sum / 10
    console.log(avg);

```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}

Ans-- error
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum(max=10){
  var sum =0;
  for(let i = 0;i<=max; i=i+1 ){
  if(i%2===0){
  sum= sum+i;}
}
return sum;
}
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js
function getOddSum(max=10){
  var sum =0;
  for(let i = 0;i<=max; i=i+1 ){
  if(i%2!==0){
  sum= sum+i;}
}
return sum;
}
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

```js
function getProductOfDigits(num){
let product=1
while(num>0){
let reminder=num%10
 num=num-reminder
 product=product*reminder
 num=num/10

}
return product
}

```

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); /* output */ Ans- Bigger then 5
check(1); /* output */ Ans- Smaller then 5
check(5); /*  output */ Ans- 5
```
Explain-- First we take function then we take parameter then we use if case  number greater then 5  then we return bigger then 5 second we take function then we take parameter then we use if case  number smaller then 5 we return smaller then 5

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); /* what will be the output*/ Ans- 'you are arya'
getOutput('John'); /* what will be the output*/ Ans- 'who are you'
getOutput(); /* what will be the output*/ Ans- 'who are you'
```
Explain-- First we do this question with function we take parameter then we use if condition and we use operator then we return

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); /* what will be the output*/ Ans- 'Who are you'
getOutput('John'); /* what will be the output */ Ans- 'Who are you'
getOutput(); /* what will be the output*/ Ans- 'Who are you'
```
Explain-- First we do this question with function we take parameter then we use if condition and we use operator then use console.log.


9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Only one return statement gets executed. If you write more than one return statements and the compiler comes across two return statements consecutively then the compiler may give you an error while compiling. But this doesn't mean you can not use more than one return statements, you may do so but setting appropriate conditions using conditional statements is required, for example…
```js

function isEven(num)

{

if(num%2==0)

{

return true;
return "True";

}

return false;}

}
```
The above code snippet has two return statements but while execution only one return statement gets executed for each run.



10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.


The 'for' loop used only when we already knew the number of iterations. The 'while' loop used only when the number of iteration are not exactly known. If the condition is not put up in 'for' loop, then loop iterates infinite times. If the condition is not put up in 'while' loop, it provides compilation error.

```js
function getProductOfDigits(num){
let product=1
while(num>0){
let reminder=num%10
 num=num-reminder
 product=product*reminder
 num=num/10

}
return product
}
```

```js
function getOddSum(max=10){
  var sum =0;
  for(let i = 0;i<=max; i=i+1 ){
  if(i%2!==0){
  sum= sum+i;}
}
return sum;
}
```