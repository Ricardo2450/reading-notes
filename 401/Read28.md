# Django CRUD and Forms

* Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers

* Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.

* action: The resource/URL where data is to be sent for processing when the form is submitted. If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.
* method: The HTTP method used to send the data: post or get.
  * The POST method should always be used if the data is going to result in a change to the server's database, because it can be made more resistant to cross-site forgery request attacks.
  * The GET method should only be used for forms that don't change user data (for example, a search form). It is recommended for when you want to be able to bookmark or share the URL.

* Django's form handling does are:
  * Display the default form the first time it is requested by the user.
    * The form may contain blank fields if you're creating a new record, or it may be pre-populated with initial values (for example, if you are changing a record, or have useful default initial values).
    * The form is referred to as unbound at this point, because it isn't associated with any user-entered data (though it may have initial values).
  * Receive data from a submit request and bind it to the form.
    * Binding data to the form means that the user-entered data and any errors are available when we need to redisplay the form.
  * Clean and validate the data.
    * Cleaning the data performs sanitization of the input fields, such as removing invalid characters that might be used to send malicious content to the server, and converts them into consistent Python types.
    * Validation checks that the values are appropriate for the field (for example, that they are in the right date range, aren't too short or too long, etc.)
  * If any data is invalid, re-display the form, this time with any user populated values and error messages for the problem fields.
  * If all data is valid, perform required actions (such as save the data, send an email, return the result of a search, upload a file, and so on).
  * Once all actions are complete, redirect the user to another page.

* Django provides numerous places where you can validate your data. The easiest way to validate a single field is to override the method clean_\<fieldname>() for the field you want to check

> ## Other reads
* [Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page)

* [Django Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views)




[Return Home](../README.md)
