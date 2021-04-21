# Forms and JS Events

## JAvaScript Form event

>The **form** property within the document object contains an array of all forms defined within the document.

**Each element within the array is a form object , the index number associated with the form object defines the order in which the form appears on the webpage.**

*The exits a number of events associated with the form element. The table below enumerates them in detail.*

Object	    |   Event Handler
----------- | --------------------------------
button	    |   onClick, onBlur, onFocus
checkbox	|   onClick, onBlur, onFocus.
FileUpLoad	|   onClick, onBlur, onFocus
hidden	    |   none
password	|   onBlur, onFocus, onSelect.
radio	    |   onClick, onBlur, onFocus
reset	    |   onReset.
select	    |   onFocus, onBlur, onChange.
submit	    |   onSubmit
text	    |   onClick, onBlur, onFocus , onChange
textarea	|   onClick, onBlur, onFocus , onChange

### Javascript Form Events : Buttons
*The main utility of a button object is to trigger an event, say an onClick() event, but a button object has no default action.*

>The are several types of buttons associated with a form:

1. submit
2. reset
3. button

**These events are fired when some click related activity is registered.**

*Event Handler*	|   *Triggered When*
--------------- | ------------------------------------------------------------------------------------
onBlur	        |   The form's select, text, or textarea field loses focus.
onChange	    |   A select , text ot textarea field has lost the focus and values are changed.
onClick	        |   An object on a form gets clicked.
onFocus	        |   a field gets input focus.
onReset	        |   The the form is reset
onSelect	    |   text within the textarea field is selected
onSubmit	    |   A form is submitted

## Javascript Form Events : Event handler onClick
**Using the event handler onClick is the most frequently used in form, or elsewhere to trigger event handler function on click events.**

`A click event is set to take place when the button within a form, radio or checkbox is pressed or when a selection is made.`

## HTML Forms

*An HTML form is used to collect user input. The user input is most often sent to a server for processing.*

>**The HTML `<form>` element is used to create an HTML form for user input**

### The `<input>` Element

**The HTML `<input>` element is the most used form element.**

*An `<input>` element can be displayed in many ways, depending on the type attribute.*

### Example
Type	|   Description
---------------------------- | ---------------------------------------
`<input type="text">`   |	Displays a single-line text input field
`<input type="radio">`  |	Displays a radio button (for selecting one of many choices)
`<input type="checkbox">`   |	Displays a checkbox (for selecting zero or more of many choices)
`<input type="submit">`   |	Displays a submit button (for submitting the form)
`<input type="button">`   |   Displays a clickable button

