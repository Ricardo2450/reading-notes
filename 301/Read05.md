# Putting it all together

> ## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
   * Single responsibility principle is where a component should ideally only do one thing. It help maps out the component structure to identify what needs to be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?
   * build a version with no interactivity.

3. Once you have a static application, what do you need to add?
   * Identify the minimal representation of UI state.

4. What are the three questions you can ask to determine if something is state?
   * Is it passed in from a parent via props? If so, it probably isn’t state.
   * Does it remain unchanged over time? If so, it probably isn’t state.
   * Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?
   * Identify every component that renders something based on that state.
   * Find a common owner component
   * Find the common owner or another component higher up in the hierarchy should own the state.

References:
[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

> ## Higher-Order Functions

1. What is a “higher-order function”?
   * Functions that operate on other functions, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
   * Its saying to return M if M is greater than N.

3. Explain how either map or reduce operates, with regards to higher-order functions.
   * Map transforms an array by applying a function to all of its elements and building a new array from the returned values.
   * Reduce builds a value by repeatedly taking a single element from the array and combining it with the current value

References:
[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

> ### Things I want to know more about

* Better understanding of what needs to have state.


[Return home](../README.md)
