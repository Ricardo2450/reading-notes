# Forms and JS Events

> ## HTML Forms

### Questions

1. Why are forms so important in web development?
   * They allow interaction between a user and a website or application. They also allow users to enter data, which is generally sent to a web server for processing and storage or used on the client-side to immediately update the interface in some way.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
   * Only for the data you absolutely need.
   * The bigger your form, the more you risk frustrating people and losing users

3. List 5 form elements and explain their importance.
   * \<form>
   : This formally defines a form.
       * It's standard practice to always set at least the action and method attributes.
          * Action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
          * Method attribute defines which HTTP method to send the data with (usually get or post).
  
   * \<label>
   : represents a caption for an item in a user interface.

   * \<input>
   : Create interactive controls for web-based forms in order to accept data from the user;

   * \<textarea>
   : The input field for the message.

   * \<button>
   : Allows the user to send, or "submit", their data once they have filled out the form.



References:
[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form),
[How To Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)


## Learn JS

### Questions

1. How would you describe events to a non-technical friend?
   * Events are like teaching your friend a new trick. You tell your friend how to do something. They process it and do trys to attempt it.

2. When using the addEventListener() method, what 2 arguments will you need to provide?
   * The name of the event we want to register and the code that comprises the function

3. Describe the event object. Why is the target within the event object useful?
   * Automatically passess to event handlers to provide extra features and information. THe target is useful because its always a reference to the element the event occurred upon.

4. What is the difference between 
event bubbling and event capturing?
   * Bubbling bubbles up from the innermost element that was clicked. Event capturing you're implicitly clicking the element it is inside.


References:
[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)


> ### Other good reads:

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types),
[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)


> ### Things I want to know more about.

* event bubbling and capturing.
* creating a button.

[Return home](../README.md)
