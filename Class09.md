# Class09 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## Forms: 

#### Why Forms?

The best known form on the web is probably the search box that sits right in the middle of Google's homepage. In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists. 

#### Form Controls: 

There are several types of form controls that you can use to collect information from visitors to your site.

* ADDING TEXT:

 1. Text input (single-line): Used for a single line of text such as email addresses and names.
 2. Password input: Like a single line text box but it masks the characters entered.
 3. Text area (multi-line): For longer areas of text, such as messages and comments.

* Making Choices:

 1. Radio buttons: For use when a user must select one of a number of options.
 2. Checkboxes: When a user can select and unselect one or more options.
 3. Drop-down boxes: When a user must pick one of a number of options from a list.

* Submitting Forms:

 1. Submit buttons: To submit data from your form to another web page.
 2. Image buttons: Similar to submit buttons but they allow you to use an image.

* Uploading Files:

File upload: Allows users to upload files (e.g. images) to a website.

#### How Forms Work? 

A user fills in a form and then presses a button to submit the information to the server. A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element. 

#### Form Structure: 

* "<form>": Form controls live inside a "<form>" element. This element should always carry the action attribute and will usually have a method and id attribute too.

 1. action: Every "<form>" element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
 2. method: Forms can be sent using one of two methods: get or post.
 3. id: We look at the id attribute before, but the value is used to identify the form distinctly from other elements on the page (and is often used by scripts — such as those that check you have entered information into fields that require values).

#### Text Input: 

* "<input>": The "<input>" element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
 
 1. type="text": When the type attribute has a value of text, it creates a singleline text input.
 2. name: When users enter information into a form, the server needs to know which form control each piece of data was entered into.
 3. maxlength: You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. 
 4. size: The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input (measured by the number of characters that would be seen). 

#### Password Input: 

* "<input>": 

 1. type="password": When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out.
 2. name: The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
 3. size, maxlength: It can also carry the size and maxlength attributes like the the single-line text input.

#### Text Area: 

* "<textarea>": The "<textarea>" element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag. 

#### Radio Button: 

* "<input>": 

 1. type="radio": Radio buttons allow users to pick just one of a number of options.
 2. name:The name attribute is sent to the server with the value of the option the user selects. When a question provides users with options for answers in the form of radio buttons, the value of the name attribute should be the same for all of the radio buttons used to answer that question.
 3. value: The value attribute indicates the value that is sent to the server for the selected option.
 4. checked: The checked attribute can be used to indicate which value (if any) should be selected when the page loads. The value of this attribute is checked. 

#### Checkbox: 

* "<input>": 

 1. type="checkbox": Checkboxes allow users to select (and unselect) one or more options in answer to a question.
 2. name: The name attribute is sent to the server with the value of the option(s) the user selects.
 3. value: The value attribute indicates the value sent to the server if this checkbox is checked.
 4. checked: The checked attribute indicates that this box should be checked when the page loads.

#### Drop Down List Box: 

* "<select>": A drop down list box (also known as a select box) allows users to select one option from a drop down list. The "<select>" element is used to create a drop down list box. It contains two or more "<option>" elements.
 - name: The name attribute indicates the name of the form control being sent to the server, along with the value the user selected.

* "<option>": The "<option>" element is used to specify the options that the user can select from. The words between the opening "<option>" and closing "</option>" tags will be shown to the user in the drop down box.
 
 1. value: The "<option>" element uses the value attribute to indicate the value that is sent to the server along with the name of the control if this option is selected.
 2. selected: The selected attribute can be used to indicate the option that should be selected when the page loads. The value of this attribute should be selected. If this attribute is not used, the first option will be shown when the page loads. If the user does not select an option, then the first item will be sent to the server as the value for this control. 

#### Multiple Select Box: 

* "<select>": 

 1. size: You can turn a drop down select box into a box that shows more than one option by adding the size attribute. Its value should be the number of options you want to show at once. 
 2. multiple: You can allow users to select multiple options from this list by adding the multiple attribute with a value of multiple. 

#### File Input Box: 

* "<input>": If you want to allow users to upload a file (for example an image, video, mp3, or a PDF), you will need to use a file input box.
 - type="file": This type of input creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.

#### Submit Button: 

* "<input>": 

 1. type="submit": The submit button is used to send a form to the server.
 2. name: It can use a name attribute but it does not need to have one.
 3. value: The value attribute is used to control the text that appears on a button. It is a good idea to specify the words you want to appear on a button because the default value of buttons on some browsers is ‘Submit query’ and this might not be appropriate for all kinds of form.

#### Image Button: 

* "<input>": 

 - type="image": If you want to use an image for the submit button, you can give the type attribute a value of image. The src, width, height, and alt attributes work just like they do when used with the "<img>" element. 

#### Button & hidden Controls: 

* "<button>": The "<button>" element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button. This means that you can combine text and images between the opening "<button>" tag and closing "</button>" tag.

 * "<input>": 

 - type="hidden": This example also shows a hidden form control. These form controls are not shown on the page. They allow web page authors to add values to forms that users cannot see. 

#### Labelling Form Controls: 

* "<label>": When introducing form controls, the code was kept simple by indicating the purpose of each one in text next to it. However, each form control should have its own "<label>" element as this makes the form accessible to vision-impaired users. The "<label>" element can be used in two ways. It can:
 
 1. Wrap around both the text description and the form input.
 2. Be kept separate from the form control and use the for attribute to indicate which form control it is a label for (as shown with the radio buttons).
 
* for: The for attribute states which form control the label belongs to. Note how the radio buttons use the id attribute. The value of the id attribute uniquely identifies an element from all other elements on a page. 

#### Grouping Form Elements: 

* "<fieldset>": You can group related form controls together inside the "<fieldset>" element. This is particularly helpful for longer forms. Most browsers will show the fieldset with a line around the edge to show how they are related. The appearance of these lines can be adjusted using CSS.

* "<legend>": The "<legend>" element can come directly after the opening "<fieldset>" tag and contains a caption which helps identify the purpose of that group of form controls.

#### Search Input: 

* "<input>": If you want to create a single line text box for search queries, HTML5 provides a special type of input for that purpose.

 1. type="search": To create the HTML5 search box the "<input>" element should have a type attribute whose value is search. Older browsers will simply treat it like a single line text box. Recent browsers add some features that improve usability.
 2. placeholder: On any text input, you can also use an attribute called placeholder whose value is text that will be shown in the text box until the user clicks in that area. 

## Lists, Tables and Forms: 

#### Bullet Point Styles (list-style-type): 

The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). It can be used on rules that apply to the "<ol>", "<ul>", and "<li>" elements.

* Unordered Lists:  For an unordered list you can use the following values:
 1. none. 
 2. disc. 
 3. circle. 
 4. square. 

* Ordered Lists: For an ordered (numbered) list you can use the following values:

 1. decimal: 1 2 3. 
 2. decimal-leading-zero: 01 02 03. 
 3. lower-alpha: a b c. 
 4. upper-alpha: A B C. 
 5. lower-roman: i. ii. iii.
 6. upper-roman: I II III. 

* Positioning the Marker (list-style-position): This property can take one of two values:

 1. outside: The marker sits to the left of the block of text. (This is the default behaviour if this property is not used.)
 2. inside: The marker sits inside the box of text (which is indented).

* List Shorthand (list-style): As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called list-style, and it allows you to express the markers' style, image and position properties in any order. 

* Border on Empty Cells (empty-cells): If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown.It can take one of three values:

 1. show: This shows the borders of any empty cells.
 2. hide: This hides the borders of any empty cells.
 3. inherit: If you have one table nested inside another, the inherit value instructs the table cells to obey the rules of the containing table. 

## Events: 

#### HOW EVENTS TRIGGER JAVASCRIPT CODE? 

When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling. 

 1. Select t he element node(s) you want the script to respond to. 
 2. Indicate which event on the selected node(s) will trigger the response. 
 3. State the code you want to run when the event occurs. 

* THREE WAYS TO BIND AN EVENT TO AN ELEMENT: Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers: 

 1. HTML EVENT HANDLERS. 
 2. TRADITIONAL DOM EVENT HANDLERS. 
 3. DOM LEVEL 2 EVENT LISTENERS. 

* USING PARAMETERS WITH EVENT HANDLERS & LISTENERS: Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround. 

Usually, when a function needs some information to do its job, you pass arguments within the parentheses that follow the
function name. When the interpreter sees the parentheses after a function call, it runs the code straight away. In an event handler, you want it to wait until the event triggers it. Therefore, if you need to pass arguments to a function that is called by an event handler or listener, you wrap the function call in an anonymous function. 

* THE EVENT OBJECT: When an event occurs, the event object tells you information about the event, and the element it happened upon. Every time an event fires, event object contains helpful  data about the event, such as: 
 * Which element the event happened on.  
 * Which key was pressed for a keypress event.  
 * What part of the viewport the user clicked for a c1ick event. 

* EVENT DELEGATION: Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element. If users can interact with a lot of elements on the page, such as:

 * a lot of buttons in the UI.
 * a long list.
 * every cell of a table.

adding event listeners to each element can use a lot of memory and slow down performance. 

* ADDITIONAL BENEFITS OF EVENT DELEGATION: 

 1. WORKS WITH NEW ELEMENTS: If you add new elements to the DOM tree, you do not have to add event handlers to the new elements because the job has been delegated to an ancestor. 
 2. SOLVES LIMITATIONS WITH this KEYWORD: this keyword was used to identify an event's target, but that technique did not work in IE8, or when a function needed parameters.
 3. SIMPLIFIES YOUR CODE: It requires fewer functions to be written, and there are fewer ties between the DOM and your code, which helps maintainability.

* CHANGING DEFAULT BEHAVIOR: The event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event: 

 1. preventDefau1t (): Some events, such as clicking on links and submitting forms, take the user to another page. 
 2. stopPropagation(): Once you have handled an event using one element, you may want to stop that event from bubbling up to its ancestor elements. 
 3. USING BOTH METHODS: You will sometimes see the following used in similar situations that are in a function: return false;. 

* WHICH ELEMENT DID AN EVENT OCCUR ON?

When calling a function, the event object's target property is the best way to determine which element the event occurred on. But you may see the approach below used; it relies on the this keyword.

 1. THE this KEYWORD: The this keyword refers to the owner of a function. On the right, this refers to the element that the event is on. 
 2. USING PARAMETERS: If you pass parameters to the function, the this keyword no longer works because the owner of the function is no longer the element that the event listener was bound to, it is an anonymous function. 

* MOUSE EVENTS: The mouse events are fired when the mouse is moved and also when its buttons are clicked.  

 1. click: Fires when the user clicks on the primary mouse button  (usually the left button if there is more than one). The c1ick  event will fire for the element that the mouse is currently over. It will also fire if the user presses the Enter key on the keyboard when an element has focus. 
 2. db1c1ick: Fires when the user clicks the primary mouse button twice  in quick succession.
 3. mouseover: Fires when the cursor was outside an element and is then moved inside it. 
 4. mouseout Fires when the cursor is over an element, and then moves  onto another element - outside of the current element or a child of it. 
 5. mousemove: Fires when the cursor is moved around an element. This event is repeatedly fired.

* KEYBOARD EVENTS: The keyboard events are fired when a user interacts with the keyboard. 

 1. input: Fires when the value of an "<input>" or "<textarea>" element changes.
 2. keydown: Fires when the user presses any key on the keyboard. If the user holds down a key, the event continues to fire repeatedly. 
 3. keypress: Fires when the user presses a key that would result in a character being shown on the screen.
 4. keyup: Fires when the user releases a key on the keyboard. 





















