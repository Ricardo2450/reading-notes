# FileIO & Exceptions

> ## [Read & Write Files in Python](https://realpython.com/read-write-files-python/)

* File path has three major parts
  * Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)
  * File Name: the actual name of the file
  * Extension: the end of the file path pre-pended with a period (.) used to indicate the file type

* double-dot (..) - Allows you to move one directory up.

* How to open a file in python is done by invoking the open() built-in function.
  * Ex. file = open('dog_breeds.txt')

* To close a file you have two options:
  * try-finally block
    * Ex. 
    
      reader = open('dog_breeds.txt')
    
      try:
      Further file processing goes here
    
      finally:
      reader.close()
  
  * With statement
    * Ex.
      with open('dog_breeds.txt') as reader:
      
      Further file processing goes here
  
  * You can also add special charactors to determain what the file will do.
    * Ex.
      with open('dog_breeds.txt', 'r') as reader:
      
      Further file processing goes here

    * 'r'	Open for reading (default)
    * 'w'	Open for writing, truncating (overwriting) the file first
    * 'rb' or 'wb'	Open in binary mode (read/write using byte data)

> ## [Exceptions in Python](https://realpython.com/python-exceptions/)

* Arrows indicates where the parser ran into the syntax error.

* Use **raise** to throw an exception if a condition occurs.

* **Assert** - checks if a certain condition is met.

* The **try and except** block in Python is used to catch and handle exceptions.

* Use **else statement**, to instruct a program to execute a certain block of code only in the absence of exceptions.

* Use the **finally clause** to catch everything else.



> ## [Read & Write Files in Python - Companion Video](https://realpython.com/courses/reading-and-writing-files-python/)


* open a file/ close a file
  * file = open('text_file.txt')
    file.close()

* How to close a file even with an error
  * use a try: finally: block or use with:

> ### Summery

* There are many ways to open a file. However it be a good habit to open and close a with once of the methods described above. The best one you want to get use to would be the with: statement.

> ### Other good reads or reviews

* [Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)

[Return Home](../README.md)
