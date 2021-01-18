# Forms

**Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.**
HTML borrows the concept of a form to refer to different
elements that allow you to collect information from visitors to
your site.
There are several types of form controls that
you can use to collect information from visitors
to your site.
Form Controls
ADDING TEXT:
Making Choices:
Submitting Forms: Uploading Files:
Password input
Like a single line text box but it
masks the characters entered.
Text input (single-line)
Used for a single line of text such
as email addresses and names.
Text area (multi-line)
For longer areas of text, such as
messages and comments.
Checkboxes
When a user can select and
unselect one or more options.
Radio buttons
For use when a user must select
one of a number of options.
Drop-down boxes
When a user must pick one of a
number of options from a list.
Image buttons
Similar to submit buttons but
they allow you to use an image.
Submit buttons
To submit data from your form
to another web page.
File upload
Allows users to upload files
(e.g. images) to a website.

# Lists, Tables and Forms

**There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.**

You can specify an image to act
as a bullet point using the
list-style-image property.
The value starts with the letters
url and is followed by a pair
of parentheses. Inside the
parentheses, the path to the
image is given inside double
quotes.
This property can be used on
rules that apply to the <ul> and
<li> elements.
The example on this page also
shows the use of the margin
property to increase the vertical
gap between each item in the
list
In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
 List markers can be given different appearances
using the list-style-type and list-style image
properties.
 Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
 Forms are easier to use if the form controls are
vertically aligned using CSS.
 Forms benefit from styles that make them feel more
interactive.

# Events

Scripts often respond to these events by updating the content of the web page (via the
Document Object Model) which makes the page feel more interactive. In this chapter, you
will learn how:
INTERACTIONS EVENTS TRIGGER CODE RESPONDS
CREATE EVENTS CODE TO USERS
Events occur when users When an event occurs, In the last chapter, you
click or tap on a link, hover or fires, it can be used saw how the DOM can
or swipe over an element, to trigger a particular be used to update a page.
t ype on the keyboard, function. Different code The events can trigger the
resize the window, or can be triggered when -kinds of changes the DOM
when the page they users interact with is capable of. This is how a
requested has loaded. different parts of the page. web page reacts to users.

Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
You can use event delegation to monitor for events
that happen on all of the children of an element.
The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 
