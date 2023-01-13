# Automation

> ## [Python Regular Expressions Tutorial](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)

* Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not
  * supported by the re module

* match() function returns a match object if the text matches the pattern.

* search() - scan through the given string/sequence, looking for the first location where the regular expression produces a match.

* group() - returns the string matched by the re. You will see both these functions in more detail later.

* . - A period. Matches any single character except the newline character.

* ^ - A caret. Matches the start of the string

* $ - Matches the end of string.

* [abc] - Matches a or b or c.

* [a-zA-Z0-9] - Matches any letter from (a to z) or (A to Z) or (0 to 9).

* \ - Backslash if the character following the backslash is a recognized escape character, then the special meaning of the term is taken
  * Else if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through
  * \ can be used in front of all the metacharacters to remove their special meaning

* \w - Lowercase 'w'. Matches any single letter, digit, or underscore.

* \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).

* \s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.

* \S - Uppercase 'S'. Matches any character not part of \s (lowercase s).

* \d - Lowercase d. Matches decimal digit 0-9.

* \D - Uppercase d. Matches any character that is not a decimal digit.

* \t - Lowercase t. Matches tab.

* \n - Lowercase n. Matches newline.

* \r - Lowercase r. Matches return.

* \A - Uppercase a. Matches only at the start of the string. Works across multiple lines as well.

* \Z - Uppercase z. Matches only at the end of the string.


> ## [Automation Ideas](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)

* automatically move files

* can automatically move and rename files.

* Can open up youtube when your favorite Youtuber uploads a video.

* Calculate compounding interest 

> ## Other reads

* [shutil](https://pymotw.com/3/shutil/)

* [Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

* [Watchdog](https://pythonhosted.org/watchdog/)

[Return Home](../README.md)
