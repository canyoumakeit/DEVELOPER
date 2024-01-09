# DEVELOPER
Each command is an element
#you put the h1, h2, comment, and p elements inside the main element. This is called nesting. 
**Nested elements should be placed two spaces further to the right of the element they are nested in.** This spacing is called indentation and it is used to make HTML easier to read.
A tag <>for an element without a closing tag</> is known as a self-closing tag.
**#HTML attributes** are special words used inside the opening tag **<element attribute>** of an element to control the element's behavior.
The src attribute in an img element specifies the image's URL (where the image is located).
**IMage text:** #All** img elements ** should have an **alt attribute**. 
The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load. For example, <img src="cat.jpg" alt="A cat"> has an alt attribute with the text A cat.
can link to another page with the** anchor (a) element**. For example, <a href='https://freecodecamp.org'></a> would link to freecodecamp.org.here href is an attribute
**Link text:** A **link's text must be placed between the opening and closing tags of an anchor (a) element**
Step 19
When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.
After the last h2 element of the second section element, add an h3 element with this text:dhff
<ul> <!--List of texts-->
 <li>milk</li>
  <li>cheese</li>
</ul>
The ** figure element** represents self-contained content and will allow you to associate an image with a caption.
The **code for an ordered list (ol**) is similar to an unordered list, but list items in an ordered list are numbered when displayed.
The** strong element** is used to indicate that some text is of strong importance or urgent.
The **action attribute** indicates where form **data should be sent**. For example, <form action="/submit-url"></form> tells the browser that the form data should be sent to the path /submit-url.
The** input element allows you several ways to collect data from a web form**. Like img elements, input elements **are self-closing** and do not need closing tags.
Inside FORM you can add input to get input and store it in nyour form location...TYPE is the attribute for INPUT element,,
In order for a form's data to be accessed by the location specified in the action attribute, you must **give the text field a name attribute** and assign it a value to represent the data being submitted. For example, you could use the following syntax for an email address text field: <input type="text" name="email">.
Placeholder text is used to give people a hint about what kind of information to enter into an input. For example, <input type="text" placeholder="Email address">.
To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.

Use the** button element to create a clickable button**. For example, <button>Click Here</button> creates a button with the text Click Here.
Add a button element with the text Submit below the input element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's action attribute.
 <button type="submit">Submit </button>
**
 label elements are used to help associate the text for an input element with the input elem**ent itself (especially for assistive technologies like screen readers). For example, <label><input type="radio"> cat</label> makes it so clicking the word cat also selects the corresponding radio button.
The i**d attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.
Add an id attribute with the value indoor to the radio button. When elements have multiple attributes, the order of the attributes doesn't matter.**
All pages should begin with **<!DOCTYPE html>**. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.
You can set browser behavior by adding self-closing **meta elements** in the head. Here's an example:
<meta attribute="value">
Tell the browser to parse the markup into multiple languages by creating a meta element as a child of the head element. Set its charset attribute to UTF-8.
