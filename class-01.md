# Html
***Hypertext Markup Language***
* the code that is used to structure a web page and its content.
* markup language that defines the structure of your content. 
* HTML consists of a series of elements like enclosing tags can make a word or image hyperlink to somewhere else.
* The main parts of our element are as follows:
# 1 The opening tag
# <p>
# 2 The closing tag
# </p>
# 3 The content
# 4 The element

## Attribute should always have the following:
* A space between it and the element name 
* The attribute name followed by an equal sign.
* The attribute value wrapped by opening and closing quotation marks
# ~~Example:~~
# <p lang="en-us">Paragraph in English</p>
# ***Structure of Html*** 
* **<body>**
###  Everything inside this element is shown inside the main browser window.
* **<head>**
### Before the <body> element you will often see a <head> element. This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a <title> element inside the <head> element.
* **<title>**
### The contents of the <title> element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).
# ~~Example:~~
### <html>
### <head>
 ### <title>This is the Title of the Page</title>
### </head>
### <body>
 ### <h1>This is the Body of the Page</h1>
 ### <p>Anything within the body of a web page is displayed in the main browser window.</p>
### </body>
### </html>

# ***Creating a Web Page on a PC***
* Start
* #### All Programs (or Programs)
* #### Accessories
* #### Notepad
### Then type the code .
### Go to the File menu and select Save as. 
### Start your web browser. Go to the File menu and select Open. Browse to the file that you just created, select it and click on the Open button. 
# ***Creating a Web Page on a Mac***
* ### start up TextEdit. This should be in your Applications folder.
#### You might also like to download a free text editor for creating web pages called TextWrangler which is available from barebones.com
* ### Type the code
* ### Now go to the File menu and select Save as
####  You will probably see a window You want to select the Use .html button.
* ### start your web browser, go to the File menu, and select Open.

# ***HTML: Markup***
# Comments <!-- -->
* Helpe you to add a comment to your code that will not be visible in the user's browser
# ~~Example:~~
#### <!-- comment goes here -->
# ID Attribute
* Every HTML element can carry the id attribute. 
* It is used to uniquely identify that element from other elements on the page.
* Its value should start with a letter or an underscore (not anumber or any other character).
* It is important that no two elements on the same page
have the same value for their id attributes (otherwise the value is no longer unique).
* The id attribute is known as a
* global attribute because it can be used on any element.
# ~~Example:~~
### <p id="pullquote">Every time I view the sea I feel a calming sense of security, as if visiting my ancestral home; I embark on a voyage of seeing.
### </p>

# Class Attribute
* Every HTML element can also carry a class attribute.
* identify several elements as being different from the other elements on the page.
* using these attributes does not affect the presentation of an element

# ~~Example:~~
#### you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. To do this you can use the class attribute. 
### The class attribute on any element can share the same value. 
### <p class="important">For a one-year period from November 2010, the Marugame Genichiro-Inokuma Museum of Contemporary Art (MIMOCA) will host a cycle of four Hiroshi Sugimoto exhibitions.
### </p>
### <p>Each will showcase works by the artist thematically contextualized under the headings "Science," "Architecture," "History" and "Religion" so as to present a comprehensive panorama of the artist's oeuvre.
### </p>
### <p class="important admittance">Hours: 10:00 – 18:00 (No admittance after 17:30)
### </p>

# Block Elements
* ### elements will always appear to start on a new line in the browser window. These are known as block level elements.
# ~~Example:~~
## <h1>, <p>, <ul>, and <li>.
# Inline Elements
* always appear to continue on the same line as their neighbouring elements. 
# ~~Example:~~
## <a>, <b>, <em>, and <img>.
# Grouping Text & Elements In a Block
# 1 <div>
* group a set of elements together in one block-level box
* you can  create a <div> element to contain all of the elements for the header of your site (the logo and the navigation), or you might create a <div> element to contain comments from visitors.
* <div> element will start on a new line, but other than this
it will make no difference to the presentation of the page.
* Using an id or class attribute on the <div> element, however, means that you can create CSS style rules to indicate how much space the <div> element should occupy on the screen and change the appearance of all the elements contained within it.
# 2 <span>
* acts like an inline 
* Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
* Contain a number of inline elements

# IFrames
* a little window that has been cut into your page — and in that window you can see another page. 
* The term iframe is an abbreviation of inline frame.
* created using the <iframe> element.
* attributes that you will need
to know to use it:
### src
##### The src attribute specifies the URL of the page to show in the frame.
### height
##### The height attribute specifies the height of the iframe in pixels.
### width
##### The width attribute specifies the width of the iframe in pixels
# ~~Example:~~
#### <iframe
#### width="450"
#### height="350"
#### src="http://maps.google.co.uk/maps?q=moma+new+york &amp;output=embed">
#### </iframe>

# Escape Characters
* Less-than sign
&lt;
&#60;
* Greater-than sign
&gt;
* Ampersand
&amp;
&#38;
* Quotation mark
&quot;
&#34;
* Cent sign
&cent;
&#162;
* Pound sign
&pound;
&#163;
* Yen sign
&yen;
&#165;
* Euro sign
&euro;
&#8364;
* Copyright symbol
&copy;
&#169;
* Registered trademark
&reg;
&#174;
* Left single quote
&lsquo;
&#8216;
* Right single quote
&rsquo;
&#8217;
* Left double quotes
&ldquo;
&#8220;
* Right double quotes
&rdquo;
&#8221;
* Multiplication sign
&times;
&#215;
* Division sign
&divide;
&#247; 
__________
# New Html5 Layout Elements
## a new set of elements that allow you to divide up the parts of a page
# 1 Headers & Footers <header> <footer>
* appears at the top or bottom of every page on the site.
* for an individual <article> or <section> within the page.
# 2 Navigation <nav>
* used to contain the major navigational blocks on the site such as the primary site navigation.
* use the <nav> element for the links that appear at the bottom of every page (links to things like privacy policy, terms and conditions and accessibility information). 
# 3 Articles <article>
* acts as a container for any section of a page that could stand alone and potentially be syndicated.
* an individual article or blog entry, a comment or forum post, or any other independent piece of content
* If a page contains several articles then each individual article would live inside its own <article> element.
* The <article> elements can even be nested inside each other.

# Asides <aside>
*  has two purposes, depending on whether it is inside an <article> element or not. 
* When the <aside> element is used inside an <article> element, it should contain information that is related to the article but not essential to its overall meaning
* When the <aside> element is used outside of an <article> element, it acts as a container for content that is related to the entire page.

# Sections <section>
* groups related content together, and typically each section would have its own heading.
* For example, on a homepage there may be several <section>
elements to contain different sections of the page, such as latest news, top products, and newsletter signup.
* Because the <section> element groups related items together, it may contain several distinct <article> elements that have a common theme or purpose.
* if you have a page with a long article, the <section> element can be used to split the article up into separate sections.

# Heading Groups <hgroup>
* purpose of the <hgroup> element is to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.

# Figures <figure> <figcaption>
* It can be used to contain any content that is referenced from the main flow of an article (not just images). 
* Examples of usage include:
● Images
● Videos
● Graphs
● Diagrams
● Code samples
● Text that supports the main body of an article
* The <figure> element should also contain a <figcaption> element which provides a text decription for the content of the <figure> element

# Linking Around Block-Level Elements
* HTML5 allows web page authors to place an <a> element around a block level element that contains child elements. This allows you to turn an entire block into a link.
____________
# ***PROCESS & Design***
* It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
* Site maps allow you to plan the structure of a site.
* Wireframes allow you to organize the information that
will need to go on each page.
* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
* You can differentiate between pieces of information
using size, color, and style. 
* You can use grouping and similarity to help simplify
the information you present.
______________
# **JavaScript**
##  a lightweight, interpreted, or just-in-time compiled programming language with first-class functions 
* it's scripting language for Web pages.
* many non-browser environments also can use it.
* JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative
# What is a script ?
* A script is a series of instructions that the computer
can follow in order to achieve a goal.
* Each time the script runs, it might only use a subset of
all the instructions.
* Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
* To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 
# THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE
* Using the document object, you can access and change what content users see on the page and respond to how they interact with it. 
* the document object has:
### PROPERTIES
##### Properties describe characteristics of the current web page
### METHODS
##### Methods perform tasks associated with the document currently loaded in the browser
### EVENTS
##### You can respond to events, such as a user clicking or tapping on an element. 
# HOW A BROWSER SEES A WEB PAGE 
* RECEIVE A PAGE AS HTML CODE
* CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
* USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN
# write script for web page 
* It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.
* The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).
* If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created. 