# Testing and Modules

> [In Tests We Trust - TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

* TDD - Test-Driven Development

* Arrange: you need to organize the data needed to execute that piece of code (input)

* Act: here you will execute the code being tested (exercise the behaviour)

* Assert: after executing the code, you will check if the result (output) is the same as you were expecting

* The cycle
  * 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)

  * ✅ Write the feature and make the test pass!

  * 🔵 Refactor the code — the first version doesn’t need to be the beautiful one


> [If name equals main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

*  Python interpreter is running that module (the source file) as the main program, it sets the special \_\_name__ variable to have a value “\_\_main__”

* If file is being imported from another module, \_\_name__ will be set to the module’s name

* Every Python module has it’s \_\_name__ defined and if this is ‘\_\_main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.

* If you import this script as a module in another script, the \_\_name__ is set to the name of the script/module.

* Python files can act as either reusable modules, or as standalone programs.

* If \_\_name__ == “main”: is used to execute some code only if the file was run directly, and not imported.


> [What on Earth is Recursion](https://www.youtube.com/watch?v=Mv9NEXX1VHc)

* Recursion is an amazing technique with the help of which we can reduce the length of our code and make it easier to read and write.

* Factorial is only defined for integers, not real numbers

* Factorial code:
int factorial (int n)

* will run the code till it can return back an answer after going through all the stacks

> ## Summery

* Overall I believe I understand recursion in my head well enough to explain to someone. As for the reads, When writing code. Make sure you are testing often to make sure you dont have any issues to address later on when you thing your done.

> ### Other good reads/watch

* [Recursion](https://www.geeksforgeeks.org/recursion/)

* [Python Modules and Packages Companion Video](https://realpython.com/courses/python-modules-packages/)

* [Google for Education: Python Lists](https://developers.google.com/edu/python/lists)

* [Google for Education: Python Strings](https://developers.google.com/edu/python/strings)

* [Python Modules and Packages](https://realpython.com/python-modules-packages/)

* [Pytest Documentation](https://docs.pytest.org/en/latest/)

* [PyTest Tutorial](https://www.guru99.com/pytest-tutorial.html)


[Return Home](../README.md)
