# In memory storage

> ## Understanding the JavaScript Call Stack

1. What is a ‘call’?
   * a call stack

2. How many ‘calls’ can happen at once?
   * one at a time

3. What does LIFO mean?
   * Last In, First Out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
   * function firstFunction() {
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

5. What causes a Stack Overflow?
   * A recursive function (a function that calls itself) without an exit point

References:
[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)


> ## JavaScript error messages

1. What is a ‘reference error’?
   * When you try to use a variable that is not yet declared you get this type os errors

2. What is a ‘syntax error’?
   * When you have something that cannot be parsed in terms of syntax

3. What is a ‘range error’?
   * Try to manipulate an object with some kind of length and give it an invalid length

4. What is a ‘type error’?
   * When the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable

5. What is a breakpoint?
   * A stopping point in your code

6. What does the word ‘debugger’ do in your code?
   * to see the history before reaching that breaking point

References:
[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

> ### Other good reads

* [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

[Return home](../README.md)
