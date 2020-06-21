

# Today's topics about Images:
   
 # **Images**

Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.

You can also achieve several interesting effects using background images. In this chapter you will learn how to:

-    Specify the size and alignment of an image using
    
-    Add background images to boxes
    
-    Create image rollovers in CSS

## How To Control the size Image?

You can control the size of an image using the `width` and `height` properties in CSS.

    img { width: 500px; height: 500px;}
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

## Align Image Using CSS
Rather than using the <img> element's align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved:

1: The float property is added to the class that was created to represent the size of the image (such as the small class in our example).

2: New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

    img{ float: left; margin-right: 10px;}
    
   
## Haw to Make image as background ?
The background-image property allows you to place  
an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.
body {  
background-image: url("images/pattern.gif");}

## Background-repeat
The background-repeat property can have four values

> repeat

The background image is repeated both horizontally and vertically (the default way it  
is shown if the background- repeat property isn't used).

> repeat-x

The image is repeated horizontally only (as shown in the first example on the left).

> repeat-y

The image is repeated vertically only.

> no-repeat

The image is only shown once.

The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:

> fixed

The background image stays in the same position on the page.

> scroll

The background image moves up and down as the user scrolls up and down the page.
The path to the image follows the letters url, and it is put inside parentheses and quotes.

## Practical Information

 1.  Search engine optimization helps visitors find your sites when using
       search engines
    2.  Analytics tools such as Google Analytics allow you to see how many
    people visit your site, how they find it, and what they do when they
    get there.
3. To put your site on the web, you will need to obtain a domain name
    and web hosting.
    
4. FTP programs allow you to transfer files from your local computer
    to your web server.
    
5. Many companies provide platforms for blogging, email newsletters,
    e-commerce and other popular website tools (to save you writing them
    from scratch)
