# Read 02- Basics of HTML, CSS & JS
This topic matters because you need to really understand the basics before trying more advance stuff with html, css, & JS. Always got to build a strong foundation first!

> ## Introduction to HTML cont.

* **presentational elements**
:  \<b>, \<i>, and \<u> are Elements which only affect presentation and not semantics.
    * They came about so people could write bold, italics, or underlined text in an era when CSS was still supported poorly or not at all. They should <strong>no longer</strong> be used because, as we've seen before, semantics is so <em>important</em> to accessibility, SEO, etc.

* \<i> is used to convey a meaning traditionally conveyed by italic: foreign words, taxonomic designation, technical terms, a thought…

* \<b> is used to convey a meaning traditionally conveyed by bold: keywords, product names, lead sentence…

* \<u> is used to convey a meaning traditionally conveyed by underline: proper name, misspelling…

* **Description list**
: To mark up a set of items and their associated descriptions. Such as terms, definitions, questions, and answers.
  * use \<dl> (Description list) as the wrapper.
  * \<dt> (description term) for each term you want to identify.
  * \<dd> (description definition) for each description.

* \<blockquote>
: used if a section of block is quoted from somewhere else.

* \<q>
: is used for inline quotations.

* \<abbr>
: Used to wrap around an abbreviation or acronym.

* \<sup> (superscript)
: to mark up something on the top part of a word like a date.
  * 25<sup>th</sup> of May. The th is using \<sup>

* \<sub> (subscript)
: to mark up something on the bottom part of a word like a chemical formulae.
  * C<sub>8</sub> The 8 is using \<sub>

### Questions

1. Why is it <strong>important</strong> to use semantic elements in our HTML?
    * so we can give what we are creating the correct meaning, function or appearance. Plus it will help us with SEO and screen readers. 

2. How many levels of headings are there in HTML?
    * There are <em>six</em> headings in HTML.

3. What are some uses for the \<sup> and \<sub> elements?
    * Dates, chemical formulae, and mathematical equations.

4. When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?
    * Title attribute.

References:
[Intro to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML),
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals),
[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

> ## Learn CSS

* Ways to apple CSS:
  * External stylesheet
    * Add by adding a .css extension. \<link rel="stylesheet" href="styles.css" />
  * Internal stylesheet
    * Place CSS inside a \<style> element contained inside the HTML \<head>.
  * Inline style
    * CSS declarations that affect a single HTML element, contained within a style attribute. \<h1 style="color: blue;background-color: yellow;border: 1px solid black;">
    * <em>Note</em>: <strong>Avoid using CSS in this way, when possible</strong>.

* **cascade**
: Later styles replace conflicting styles that appear earlier in the stylesheet.

* **specificity**
: A class is rated as being more specific, as in having more specificity than the element selector, so it cancels the other conflicting style declaration.

* **Properties**
: human-readable identifiers that indicate which stylistic features you want to modify.

* **Values**
: Each property is assigned a value. This value indicates how to style the property.
  
  * <em>Note</em>: When a property is paired with a value, this pairing is called a CSS declaration. Declarations are found within CSS Declaration Blocks.
  
  * <em>Note</em>: CSS properties and values are case-insensitive and are separated by a colon (:) 

* **CSS declarations**
: CSS declaration blocks are paired with selectors to produce CSS rulesets (or CSS rules).

* **Shorthand properties**
: Font, background, padding, border, and margins.
  * This is because shorthand properties set several values in a single line.

* **Comments**
: To start a comment \/* and end a comment \*/

### Questions

1. What are ways we can apply CSS to our HTML?

   * External stylesheet
   * Internal stylesheet
   * Inline style

2. Why should we avoid using inline styles?

* Might require multiple edits to the webpage. Also, it will mix CSS presentational code with HTML and content. Making things hard to understand.

3. Review the block of code below and answer the following questions:
   1. What is representing the selector?
      * h2

   2. Which components are the CSS declarations?
      * { }

   3. Which components are considered properties?
      * color and padding.

h2 {
     color: black;
     padding: 5px;
   }

References:
[How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

> ## Learn JS

### Questions

1. What data type is a sequence of text enclosed in single quote marks?
   * String
2. List 4 types of JavaScript operators.
   * Addition
   * strict equality
   * assignment
   * Not, Does-not-equal

3. Describe a real world Problem you could solve with a Function.

* When a user clicks on a click event. Once clicked, the browser will run the code which should have some functions associated with it.

References:
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

> ## Making Decisions In Your Code – Conditionals

* **Conditional statements**
: Statements where a hypothesis is followed by a conclusion.

* **If-else statements**
: Executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed.

* **Else if**
: Extra choices/outcomes to your if...else statement.
   * It is perfectly OK to put one if...else statement inside another one — to nest them

* **Comparison operators**
: used to test the conditions inside our conditional statements.
  * === and !== — test if one value is identical to, or not identical to, another.
  * < and > — test if one value is less than or greater than another.
  * <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

* **logical operators**:
   * && — AND; allows you to chain together two or more expressions so that <strong>all</strong> of them have to individually evaluate to true for the whole expression to return true.
   * \|\| — OR; allows you to chain together two or more expressions so that <strong>one</strong> or more of them have to individually evaluate to true for the whole expression to return true.
   * ! - Not operator, can be used to negate an expression.
* <em>Note</em>: You can combine as many logical statements together as you want, in whatever structure. 

### Questions

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.

   * Checks a **condition** and if **True**, the code will be executed.

2. What is the use of an else if?
   * Extra choices/outcomes to your if...else statement.

3. List 3 different types of comparison operators.
   * === and !==
   * < and > 
   * <= and >=

4. What is the difference between the logical operator && and \|\|?
   * AND operator **all** expressions have to individually evaluate to true. While the OR operator only **one** or more expressions have to evaluate to true.

References:
[Making Decisions In Your Code – Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

> ## Things I want to know more about.

* citing stuff correctly.
* Marking up times and dates
* Events
* onclick

Other good reads:

[Write a Git Commit Message](https://cbea.ms/git-commit/)

[Return to home page](../README.md)
