# Pythonisms

> ## [Dunder Methods](https://dbader.org/blog/python-dunder-methods)

* Dunder methods let you emulate the behavior of built-in types

* Python data model lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access

* \_\_repr\_\_: The “official” string representation of an object

* \_\_str\_\_: The “informal” or nicely printable string representation of an object

* You can make an object callable like a regular function by adding the \_\_call\_\_ dunder method

> ## [Iterators](https://dbader.org/blog/python-iterators)

* iterators provide a common interface that allows you to process every element of a container while being completely isolated from the container’s internal structure.

* Python iterators normally can’t be “reset”—once they’re exhausted they’re supposed to raise StopIteration every time next() is called on them.

* In Python 3, the method that retrieves the next value from an iterator is called \_\_next\_\_

* Iterators provide a sequence interface to Python objects that’s memory efficient and considered Pythonic

* To support iteration an object needs to implement the iterator protocol by providing the __iter__ and __next__ dunder methods.

* Class-based iterators are only one way to write iterable objects in Python.

> ## [Generators](https://dbader.org/blog/python-generators)

* a yield statement suspends the function and retains its local state.

* Generator functions are syntactic sugar for writing objects that support the iterator protocol. Generators abstract away much of the boilerplate code needed when writing class-based iterators.

* The yield statement allows you to temporarily suspend execution of a generator function and to pass back values from it.

* Generators start raising StopIteration exceptions after control flow leaves the generator function by any means other than a yield statement.

> ## Other videos and reads

* [What are Generators](https://realpython.com/lessons/what-are-python-generators/)

* [Decorators](https://realpython.com/primer-on-python-decorators/)

[Return Home](../README.md)
