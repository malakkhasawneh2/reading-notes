# Form Controls
* several types of form controls that you can use to collect information from visitors to your site.
  - ADDING TEXT
  <img src="img/t3.PNG">
  - Making Choices:
  <img src="img/t4.PNG">
  - Submitting Forms
  - Uploading Files
    <img src="img/t2.PNG">

# How Forms Work
* A user fills in a form and then presses a button to submit the information to the server.
* The name of each form control is sent to the server along with the value the user enters or selects.
* The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database
* The server creates a new page to send back to the browser based on the information received.
    <img src="img/t5PNG.PNG">

# Form Structure
* < form>
  - Form controls live inside a < form> element. This element should always carry the action attribute and will usually have a method and id attribute too 
*  action
  - Every < form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
* method
  - Forms can be sent using one of two methods: get or post.

<img src="img/t6.PNG">

# Text Input
* < input>
  - The < input> element is used to create several different form controls. 
  - The value of the type attribute determines what kind of input they will be creating.
* type="text"
  - When the type attribute has a value of text, it creates a singleline text input.
* name
  - When users enter information into a form, the server needs to know which form control each piece of data was entered into.   
* maxlength
  - You can use the maxlength attribute to limit the number of characters a user may enter into the text field. 
* size
  - The size attribute should not be used on new forms. It was used in older forms to indicate the width of the text input

<img src="img/t7.PNG">

# Password Input
* type="password"
  - When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out.
* name
  - The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
* size, maxlength
  - It can also carry the size and maxlength attributes like the the single-line text input.

<img src="img/t8.PNG">

# Text Area
* The < textarea > element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag.
<img src="img/t9.PNG">

# Radio Button
<img src="img/t10.PNG">

# Checkbox
<img src="img/t11.PNG">

# Drop Down List Box
* < select>
  - A drop down list box (also known as a select box) allows users to select one option from a drop down list. 
* < option>
  - The < option> element is used to specify the options that the user can select from.

<img src="img/t12.PNG">

# Multiple Select Box

<img src="img/t13.PNG">

# File Input Box
<img src="img/t14.PNG">

# Submit Button
<img src="img/t15.PNG">

# Image Button
<img src="img/t16.PNG">

# Button & hidden Controls
<img src="img/t17.PNG">









