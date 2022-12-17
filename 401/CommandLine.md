# The Command Line

> ## The Command Line - What is it, how does it work and how do I get to one

* The command line also known as the terminal, is a text based interface to the system.
* There must be a space between the command and the first command line argument.
* Mac users - you'll find the program Terminal under Applications -> Utilities.
  * Shortcut:
   'command + space' which will bring up Spotlight, then type Terminal.
* Linux users - you'll find it in Applications -> System or Applications -> Utilities.
  * Shortcut:
   'right-click' on the desktop and there may be an option 'Open in terminal'.
* Shell:
 Part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.

> ## Basic Navigation - An introduction to the Linux directory system and how to get around it

* pwd: Print Working Directory.
  * Tells you what your current or present working directory is.

* ls: Short for list.

* There are 2 types of paths
  * absolute and relative.

  * A path is a means to get to a particular file or directory on the system.
    * Ex- file or directory on the command line
* Root directory - It is denoted by a single slash ( / ). It has subdirectories, they can have subdirectories.

* Absolute path - specify a location (file or directory) in relation to the root directory.

* Relative paths specify a location (file or directory) in relation to where we currently are in the system.

* ~ (tilde) - Shortcut for your home directory.
* . (dot) - Reference to your current directory.
* .. (dotdot)- Reference to the parent directory.

* cd - Stands for change directory.
  * It will allow us to move around in the system.
  * Without any arguments. It will take you back to your home directory.

> ## More About Files - Find out some interesting characteristics of files and directories in a Linux environment

* Linx is case sensitive.

* Quotes - use either single or double quotes. Anything inside quotes is considered a single item.

* backslash ( \ ) - Escape (or nullify) the special meaning of the next character.

* ls -a -
List the contents of a directory, including hidden files.

> ## Manual Pages - Learn how to make the most of the Linux commands you are learning

* Manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept.

* How to involk manual pages:
man \<command to look up>
  * To exit the man pages press 'q' for quit.

* keyword search: man -k \<search term>

> ## File Manipulation - How to make, remove, rename, copy and move files and directories

* mkdir - Make Directory. Used for creating a directory.

* -p - Tells mkdir to make parent directories as needed.
  * Ex. mkdir -p

* -v - Makes mkdir tell us what it is doing
  * Ex. mkdir -pv

* rmdir - Stands for remove directory.
  * **Note**: There is no undoing what you delete.
  * rmdir supports the -v and -p options
  * Ex. rmdir [options] \<Directory>

* touch - To create a file.
  * Ex. touch [options] \<filename>

* cp - Stands for copy.
  * Ex. cp [options] \<source> \<destination>

* -r option - Stands for recursive.

* mv - Short for move.
  * mv [options] \<source> \<destination>
  * Can also use mv to rename a file.
    * An example in terminal:

    terminal: ls

    foo

    terminal: mv foo foo3

    terminal: ls

    foo3

* rm - Stands for remove.
  * **Note**: removing a file is an action that may not be undone.
  * -r option with rm - allows us to remove directories and all files and directories contained within.
    * Ex. rm -r \<file name>

> ### Summery

* Overall this read was a great refresher to what I been learning and one I will come back to in the future if I need help. Plus, I had learned a few more things to work with like how to copy, delete, or look up what a command does in my terminal. 

> [Cheat Sheet - A quick reference for the main points covered in this tutorial](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

References:

* [ryans tutorials](https://ryanstutorials.net/linuxtutorial/)

[Return home](../README.md)
