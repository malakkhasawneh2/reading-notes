# **Links**
# Writing Links
* Links are created using the < a > element. Users can click on anything between the opening < a > tag and the closing < /a > tag. You specify which page you want to link to using the href attribute
<img src="https://www.wikihow.com/images/thumb/c/ce/Add-a-Hyperlink-with-HTML-Step-4-Version-3.jpg/v4-460px-Add-a-Hyperlink-with-HTML-Step-4-Version-3.jpg">

# Linking to Other Sites
* < a >
  - has an attribute called href. 
  - The value of the href attribute is the page that you want people to go to when they click on the link
  - Users can click on anything that appears between the opening < a> tag and the closing < /a > tag and will be taken to the page specified in the href attribute.

<img src="https://www.computerhope.com/jargon/h/html-tag.gif">

# Linking to Other Pages on the Same Site
* When you are linking to other pages within the same site

<img src="https://image1.slideserve.com/2083257/linking-to-other-pages-on-the-same-site-l.jpg">

# Directory Structure
* organize the code by placing the pages for each different section of the site into a new folder
  - Structure
    - The top-level folder is known as the root folder
    - The root folder contains all of the other files and folders for a website. 
    - Each section of the site is placed in a separate folder; this helps organize the files.
  - Relationships
    - relationship between files and folders on a website is described using the same terminology as a family tree. 
  - Homepages
    - The main homepage of a site written in HTML (and the homepages of each section in a child folder) is called index.html.  

<img src="https://docs.jboss.org/jbossas/admindevel326/html/images/jboss_directory_structure.jpg">

# Relative URLs
*  can be used when linking to pages within your own website
* They provide a shorthand way of telling the browser where to
find your files.
* you can create links between pages when they are only on your personal computer

<img src="https://slidetodoc.com/presentation_image_h/a0122d0c0fb2c9fe1e51955bdeea3e65/image-49.jpg">

# Email Links
* mailto: 
  - To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

<img src="https://i0.wp.com/digitalfortress.tech/wp-content/uploads/2018/05/mail-to.png?resize=672%2C377&ssl=1">

# Opening Links in a New Window
* target
  - use the target attribute on the opening < a> tag. The value of this attribute should be _blank

<img src="https://i.ytimg.com/vi/OJpDz-w0tag/maxresdefault.jpg">

_______________________
_______________________
# Normal Flow
* position:static
* In normal flow, each block-level element sits on top of the next one
* do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position: static; 
<img src="https://image.slidesharecdn.com/css-160124050959/95/css-79-638.jpg?cb=1453612252">

# Relative Positioning
* position:relative
* Relative positioning moves an element in relation to where it would have been in normal flow
* You can indicate that an element should be relatively positioned using the position property with a value of relative.
* You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow
* To move the box up or down, you can use either the top or bottom properties.
<img src="https://www.oreilly.com/library/view/web-programming-with/9781284091809/images/9781284093698_CH05_FIG20B.jpg">

# Absolute Positioning
* position:absolute
* When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. 
* The box offset properties (top or bottom and left or right) specify where the element should appear in relation to its containing element
# Fixed Positioning
* Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.
* It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.

# Overlapping Elements
* z-index
* When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. 
* If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.
# Floating Elements
* float
* The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
* Anything else that sits inside the containing element will flow around the element that is floated.
* When you use the float property, you should also use the width property to indicate how wide the floated element should be

# Clearing Floats
* clear
* The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. 
* It can take the following values:
  - left
    - The left-hand side of the box should not touch any other elements appearing in the same containing element.
  - right
    - The right-hand side of the box will not touch elements appearing in the same containing element.
  - both
    - Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
  - none
    - Elements can touch either side

_________________
_________________
# WHAT IS A FUNCTION?
* Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

<img src="https://www.learnsimpli.com/wp-content/uploads/2020/02/5-4.png">

* FUNCTION DECLARATION
  - creates a function that you can call later in your code.
  - In order to call the function later in your code, you must give it a name, so these are known as named functions
* FUNCTION EXPRESSION
  - If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression
  - A function with no name is called an anonymous function

<img src="https://i.stack.imgur.com/bCrSm.png">

# LOCAL VARIABLES
* When a variable is created inside a function using the var keyword, it can only be used in that function. It is called a local variable or function-level variable. It is said to have local scope or function-level scope.
# GLOBAL VARIABLES
* If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.

_______________
_______________
# 6 Reasons for Pair Programming
* How does pair programming work?
   - involves two roles: the Driver and the Navigator. 
* Why pair program?
  - Greater efficiency
  - Engaged collaboration
  - Learning from fellow students
  - Social skills
  - Job interview readiness
  - Work environment readiness   







