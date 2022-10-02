# Read 01- Introductory HTML and JavaScript

This topic matteres because in order to create a webpage, you first need to understand the basics and how HTML and JavaScript work. Without the fundamentals and understanding the why to it all. You will never be able to create a properly working webpage.  

> # Getting Started

* ***HTTP (Hypertext Transfer Protocol)***
: defines a language for clients and servers to speak to each other.

* ***Code files***
: Websites built primarily from HTML, CSS, and JavaScript.

* ***Assets***
: collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

1. **Compose a short poem describing how HTTP sends data between computers.**
   * browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.

2. **Describe how HTML, CSS, and JS files are “parsed” in the browser.**
   * HTML, CSS, JS files are prased by the browser reading the HTML file first. Which than leads to the browser to recognize any link or script elements to reference. If any element references are found. It sends a request back to the server than parses the CSS, JS elements. browser than generates an in-memory DOM tree from HTML, CSSOM structure for CSS and complies and executes the parsed JS.

3. **How can you find images to add to a Website?**
    * You can find images to add to a website by googling it, saving any image in a folder on your computer, or copy the image web address.

4. **How do you create a String vs a Number in JavaScript?**
    * To create a String. Just encolse what you want a string in single quote marks. \'This is a string'

    * To crate a Number. Dont put quotes around the number.

5. **What is a Variable and why are they important in JavaScript?**
    * A variable are containers that store values.

    * They are necessary to do anything interesting in programming.

References:

[Getting Started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

[How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Website design and process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

> ## Introduction to HTML

* ***Nesting***
: Elements can be placed within other elements.

  * Example of correct nesting: \<p>My cat is \<strong>very\</strong> grumpy.\</p>
  * Note: For proper nesting, we should close the strong element first, before closing the p.

* **\<span>** 
: An inline non-semantic element, which should only be used if you can't think of a better semantic text element to wrap your content, or don't want to add any specific meaning.

* **\<div>**
: A block level non-semantic element, which you should only use if you can't think of a better semantic block element to use, or don't want to add any specific meaning.

1. **What is an HTML attribute?**
    * Attribute contain extra information about the element that won't appear in the content.

2. **Describe the Anatomy of an HTMl element.**
    * The anatomy of an HTML element are the opening tag, the closing tag, and the content inside the tag.  

3. **What is the Difference between \<article> and \<section> element tags?**
    * ***Article*** is a block of related content that makes sense on its own without the rest of the page.
    * ***Section*** is similitar to article but it is more for grouping together a single part of the page that constitutes one single piece of functionality or a theme.

4. **What Elements does a “typical” website include?**

    * Most website usually include:
      * Hader
      * Nav bar
      * Main content
      * Sidebar
      * Footer

5. **How does metadata influence Search Engine Optimization?**
    * It helps add keywords relating to the content of your page. resulting in the potential to make your page appear higher in relevant searches performed in search engines.

6. **How is the \<meta> HTML tag used when specifying metadata?**
    * Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document

References:

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

[Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomy_of_an_html_document)

[HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

> ## How to start to design a Website.

1. **What is the first step to designing a Website?**

    * Come up with a project ideation and Create a list of all the ideas/goals you want to reach. 

2. **What is the most important question to answer when designing a Website?**

* Is it reasonable to build a single website to cover all those ideas/goals you created? Is it better to use existing websites instead.

References:

[How to start to design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

> ## Semantics

* **Semantics**
: Refers to the meaning of a piece of code

1. **Why should you use an \<h1> element over a \<span> element to display a top level heading?**
    * \<h1> has a semantic element. Giving it meaning so most browse's understand what its trying to say. As for \<span>, its mainly just a way to style the wording to make it look like a semantic element but doesn't give it semantic value.

2. **What are the benefits of using semantic tags in our HTML?**

    * Search engines will consider its contents as important keywords to influence the page's search rankings.
    * Screen readers can use it as a signpost to help visually impaired users navigate a page
    * Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
    * Suggests to the developer the type of data that will be populated
    * Semantic naming mirrors proper custom element/component naming

References:

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

> ## What is JavaScript?

1. **Describe 2 things that require JavaScript in the Browser?**
    * DOM (Document Object Model) API which allows you to manipulate HTML and CSS to dynamically apply new styles to your page. Another thing that require JavaScript is Audio and Video APIs. These allow you to play around with multimedia like play audio and video on your webpage.

2. **How can you add JavaScript to an HTML document?**
    * You can add JavaScript by using the \<script> tag. There are two ways to add the script tag.
        * External JavaScript
        * Inline JavaScript

References:

[What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

> ## Things I want to know more about.

* \<meta charset=""> or metadata
* Best practice for line breaks in code.
* adding favicon.
* JavaScript

[Return to home page](../README.md)