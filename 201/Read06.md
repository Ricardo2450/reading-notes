# Read 06- Problem Domain, Objects, and the DOM

> ## JavaScript Object Basics

* To call a constructor, use new. ex: const salva = new Person("Salva");



### Questions

1. How would you describe an object to a non-technical friend you grew up with?
   * An object is like when you create a new profile. The info you enter is collected and they use that info to create personal messages for you.

2. What are some advantages to creating object literals?
   * shorter syntax
   * Can transfer a series of structured, related data items in some manner
   * Sending a single object is much more efficient than sending several items individually to a database.

3. How do objects differ from arrays?
   * Objects map strings to values. While arrays map numbers to values.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
   * If an object property name is held in a variable.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

       const dog = {
  
       name: 'Spot',
  
       age: 2,
  
       color: 'white with black spots',
  
       humanAge: function (){
       console.log(`${this.name} is ${this.age*7} in human years`); 
         }
       }

* The term 'this.' refers to the current object the code is being written inside.
  * 'this.name' = Spot
  * 'this.age*7' = 14

* The benefits is that it enables you to use the same method definition for every object you create.

References:
[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

> ## Introduction To The DOM

### Questions

1. What is the DOM?
   * Document Object Model (DOM)
  : The data representation of the objects that comprise the structure and content of a document on the web.

2. Briefly describe the relationship between the DOM and JavaScript.
   * JS uses DOM to access the context of a document and its elements. Without it, JS wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

References:
[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

Other reads:

* [Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

* [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)


> ## This I want to know more about

* An example of why you would use a bracket notation over a dot notation.

[Return to home page](../README.md)
