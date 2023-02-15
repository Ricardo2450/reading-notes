# React 2

> ## [React - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

* **NOTE:** Read from conditional rendering through thinking in react.

* Conditional rendering in React works the same way conditions work in JavaScript

* use variables to store elements. This can help you conditionally render a part of the component while the rest of the output doesn’t change.

* You may embed expressions in JSX by wrapping them in curly braces

* true && expression always evaluates to expression, and false && expression always evaluates to false.

* returning a falsy expression will still cause the element after && to be skipped but will return the falsy expression

*  condition ? true : false.

* You can build collections of elements and include them in JSX using curly braces {}.

* A “key” is a special string attribute you need to include when creating lists of elements

* Keys help React identify which items have changed, are added, or are removed.

* don’t use indexes for keys if the order of items may change.

* mutable state is typically kept in the state property of components, and only updated with setState().

* \<select> creates a drop-down list

* setState() automatically merges a partial state into the current state, we only needed to call it with the changed parts.

* use the special children prop to pass children elements directly into their output

* Props and composition give you all the flexibility you need to customize a component’s look and behavior in an explicit and safe way.

> ## Other reads

* [React - Comprehensive Guide](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/)

* [Heroicons](https://heroicons.com/)



[Return Home](../README.md)
