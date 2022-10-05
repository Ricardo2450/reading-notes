# HTML Lists, Control Flow with JS, and the CSS Box Model

> ## Learn HTML: Ordered and Unordered list

* **Ordered list** \<ol>
: typically rendered as a numbered list. The order is meaningful.

* **Unordered list** \<ul>
: For grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless

* <strong>Note</strong>
: The \<ul> and \<ol> elements may be nested as deeply as desired. Moreover, the nested lists may alternate between \<ol> and \<ul> without restriction.

### Questions

1. When should you use an unordered list in your HTML document?
   * When you want to group together a collection of items that have no numerical order.

2. How do you change the bullet style of unordered list items?
   * In CSS using the list-style-type property.

3. When should you use an ordered list vs an unorder list in your HTML document?
   * Use an ordered list when you want to have the order be meaningful or numbered. Use a unordered list when you don't want a numerical order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?
   * You can change the numbers on a list by using the type attribute or use 'Start'.

References:
[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML),
[Ordered list](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol),
[Unordered list](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

> ## Learn CSS: The Box Model

* CSS broadly have two types of boxes: 
   * block boxes 
   * inline boxes

* Boxes have an inner display type and an outer display type.

* **Outer display type of** ***Block***
:
   * The box will break onto a new line.
   * The width and height properties are respected.
   * Padding, margin and border will cause other elements to be pushed away from the box.
   * The box will extend in the inline direction to fill the space available in its container. In most cases, the box will become as wide as its container, filling up 100% of the space available.

* **Outer display type of** ***inline***
:
   * The box will not break onto a new line.
   * The width and height properties will not apply.
   * Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
   * Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.

* **inner display type**
: Dictates how elements inside that box are laid out.

* <strong>Note</strong>
: Changing the value of the display property can change whether the outer display type of a box is block or inline

* Parts of making up a block box in CSS
: 
   * **Content box**
   : The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
   * **Padding box**
   : The padding sits around the content as white space; size it using padding and related properties.
   * **Border box**
   : The border box wraps the content and any padding; size it using border and related properties.
   * **Margin box**
   : The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.
     * <storng>Note</strong>: The margin is not counted towards the actual size of the box. The box's area stops at the border. It does not extend into the margin.

### Questions

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

   * A Margin acts as a barrier that pushes other elements away from the box it surrounds.

   * Padding is like a bubble that surrounds the content area and is used to push the content away from the border.

2. List and describe the four parts of an HTML elements box as referred to by the box model.

   * **Content box**
   : The area where your content is displayed.
   * **Padding box**
   : The padding sits around the content as white space.
   * **Border box**
   : The border box wraps the content and any padding.
   * **Margin box**
   : The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements.

References:
[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
[The Box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

> ## Learn JS: Arrays, Operators & Expressions, Conditionals, Loops

* Arrays
: Single objects that contain multiple values stored in a list.
  * consist of square brackets and items that are separated by commas.

* indexOf()
: To find the index of a particular item.

*  push()
: To add one or more items to the end of an array.

* unshift()
: To add an item to the start of the array.

* pop()
: To remove the last item from the array.

* shift()
: To remove the first item from an array.

* splice()
: If you know the index of an item, you can remove it from the array.

* for...of
: to access every item in the array.

* map()
: to do the same thing to each item in an array, leaving you with an array containing the changed items..

* filter()
: create a new array containing only the items in the original array that match some test.

* split()
: takes a single parameter, the character you want to separate the string at, and returns the substrings between the separator as items in an array.

### Questions

1. What data types can you store inside of an Array?
   * Numbers, strings, boolean values (true and false), characters, objects and so much more.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
   * I believe so if you create the right array with a variable for it. You can access them by doing a for...of statement.

3. List five shorthand operators for assignment in javascript and describe what they do.
   * \+= (Addition assignment)
   : adds the value of the right operand to a variable and assigns the result to the variable
   * \|\|= (logical OR assignment)
   : only assigns if x is falsy.
   * \*= (multiplication assignment)
   : multiplies a variable by the value of the right operand and assigns the result to the variable.
   * \/= (division assignment)
   : divides a variable by the value of the right operand and assigns the result to the variable
   * \%=(remainder assignment)
   : divides a variable by the value of the right operand and assigns the remainder to the variable.

4. Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
  
let b = 'dog';
 
 let c = false;

 // evaluate this
 :
 (a + c) + b;

  * The inside the parentheses A and C become the number 10. Thats because of Arithmetic operators. THe Unary Plus operator, attempts to convert the operand to a number, if it is not already. regardless if its a boolean. Now we have 10 + b. With b being a string. Its going to change the datatype of 10 into a string as well. So the answer we will get is **10dog** with a datatype being a string.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
   * a child being asked for help with a chore by their mother or father. So the condition is if the child helps. They will get extra money. If not, they will not get extra money. 

6. Give an example of when a Loop is useful in JavaScript.
   * whenever you want to run something a bunch of time. Like draw a circle a 1000 times. Loops make it simple.

References:
[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript),
[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays),
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators),
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals),
[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

> ## Things I want to know more about.
* preloading 
* better understanding about the box model.
* Is the people array a valid JavaScript array?


[Return to home page](../README.md)
