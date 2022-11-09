# Passing Functions as Props

> ## React Docs - lists and keys

1. What does .map() return?
   * an array of numbers

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
   * use curly braces {}

3. Each list item needs a unique ____.
   * key
4. What is the purpose of a key?
   * Help React identify which items have changed, are added, or are removed.

References:
[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

> ## The Spread Operator

1. What is the spread operator?
   * three dots (...)

2. List 4 things that the spread operator can do.
   * Copying an array
   * Concatenating or combining arrays
   * Adding an item to a list
   * Adding to state in React

3. Give an example of using the spread operator to combine two arrays.
   * const helloWorld = {...hello,...world}

4. Give an example of using the spread operator to add a new item to an array.
   * const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

5. Give an example of using the spread operator to combine two objects into one.
   * const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

References:
[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)


> ## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
   * Create a function

2. In your own words, what does the increment function do?
   * Its a function that can be used as many times that will update the state when a event happens.

3. How can you pass a method from a parent component into a child component?
   * by putting the method in the increment function and invoking it in the child?

4. How does the child component invoke a method that was passed to it from a parent component?
   * by using the increment function. increment={this.increment}

References:
[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

> ### Other good reads
* [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

* [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)


> ### Things I want to know more about
* More about the spread operator

[Return home](../README.md)
