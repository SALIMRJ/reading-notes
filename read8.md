# Layout

**In this chapter we are going to look at how to control where each element sits on a page and how to create attractive page layouts.**

## Building Blocks

CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors. 

## Containing Elements

If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

To indicate where a box should be positioned, you may also need to use
box offset properties to tell the browser how far from the top or bottom
and left or right it should be placed.

# Screen Sizes

**Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.**

When designing for print, you
always know the size of the
piece of paper that your design
will be printed on. However,
when it comes to designing for
the web, you are faced with the
unique challenge that different
users will have different sized
screens.
Since computers have been sold
to the public, the size of screens
has been steadily increasing.
This means that some people
viewing your site might have 13
inch monitors while others may
have 27+ inch monitors.
The size of a user's screen
affects how big they can open
their windows and how much
of the page they will see. There
are also an increasing number
of handheld devices (mobile
phones and tablets) that have
smaller screens.

Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens


Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens)
