




# Today's topics about Layout CSS:
 

>  **Building Blocks**

 CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

> **Containing Eelements**

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.

ControLLing the position of eLements
1. normal flow
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width  
of the boxes and there is space for two elements to sit side-by- side, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else)

2. relative Positioning
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

3. Absolute Positioning
This positions the element  
in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position  
of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

4. fixed Positioning
This is a form of absolute positioning that positions  
the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.
5. floating elementt
Floating an element allows you to take that element out  
of normal flow and position  
it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.


 **summary**
 1.  `<div`>` elements are often used as containing elements to group together sections of a page.
8.  Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
9. The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
10. Pages can be fixed width or liquid (stretchy) layouts.
11. Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
12. Grids help create professional and flexible designs.
13. CSS Frameworks provide rules for common tasks. X You can include multiple CSS files in one page.



