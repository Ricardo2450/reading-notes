# Classes and Objects

> ## [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)

* Objects are an encapsulation of variables and functions into a single entity

* Objects get their variables and functions from classes. 

* Classes are essentially a template to create your objects.

* You can create multiple different objects that are of the same class(have the same variables and functions defined)

* Each object contains independent copies of the variables defined in the class.

> ## [Thinking Recursively](https://realpython.com/python-thinking-recursively/)

* A recursive function is a function defined in terms of itself via self-referential expressions.
  * This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result.

* A data structure is recursive if it can be deﬁned in terms of a smaller version of itself.
  * A list is an example of a recursive data structure.
  * Other examples include set, tree, dictionary, etc

* Recursive data structures and recursive functions go together

* The recursive function’s structure can often be modeled after the definition of the recursive data structure it takes as an input.

> ## [Pytest Fixtures and Coverage](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)

* In pytest, you define fixtures using a combination of the pytest.fixture decorator, along with a function definition.

* fixtures are used differently from global variables

* fixture might act like data too.

* If you want to set up an object and then use it multiple times without creating it again. You can do that by setting the fixture's "scope"

> ### Other good reads
[Pytest Fixtures](https://docs.pytest.org/en/latest/fixture.html)

[Return Home](../README.md)
