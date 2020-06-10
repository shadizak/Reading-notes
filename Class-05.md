


 
# Today's topics are interesting and enjoyable:

**>  1. Images in HTML**
**>  2. Color in HTML**
**>  3. Text in HTML**

> # 1. Images in Links:
 - How to add images to pages  
 - Choosing the right format
 - Optimizing images for the web

### There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

## HTML Images Syntax

In HTML, images are defined with the  `<img>`  tag.

The  `<img>`  tag is empty, it contains attributes only, and does not have a closing tag.

The  `src`  attribute specifies the URL (web address) of the image:

    <img src="_url_">
## The Alt Attribute

The  `alt`  attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the  `alt`  attribute should describe the image:## The alt Attribute

The  `alt`  attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the  `alt`  attribute should describe the image:

    <img src="img_chania.jpg"  alt="Flowers in Chania">
If a browser cannot find an image, it will display the value of the `alt` attribute.

###  Image Size - Width and Height

You can use the  `style`  attribute to specify the width and height of an image.

    <img src="img_girl.jpg"  alt="Girl in a jacket"  style="width:500px;height:600px;">
Alternatively, you can use the  `width`  and  `height`  attributes:

    <img src="img_girl.jpg"  alt="Girl in a jacket"  width="500"  height="600">
The `width` and `height` attributes always define the width and height of the image in pixels.

###  Width and Height, or Style?

The  `width`,  `height`, and  `style`  attributes are valid in HTML.

However, we suggest using the  `style`  attribute. It prevents styles sheets from changing the size of images:

    <!DOCTYPE html>  
    <html>  
    <head>  
    <style>  
    img  {  
    width:  100%;  
    }  
    </style>  
    </head>  
    <body>  
      
    <img src="html5.gif"  alt="HTML5 Icon"  width="128"  height="128">  
    <img src="html5.gif"  alt="HTML5 Icon"  style="width:128px;height:128px;">  
      
    </body>  
    </html>


   ## Three rules for CreatIng Images
   There are three rules to remember when you are creating images for your website which are summarized below. We go into greater detail on each topic over the next nine pages.

1. Save Images In the rIght format
Websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load.

2. Save Images at the rIght sIze
You should save the image at the same width and height it will appear on the website. If  
the image is smaller than the width or height that you have specified, the image can be distorted and stretched. If the image is larger than the width and height if you have specified, the image will take longer to display on the page.

3. Use the correct resolutIon
Computer screens are made up of dots known as pixels. Images used on the web are also made up of tiny dots. Resolution refers to the number of dots per inch, and most computer screens only show web pages at 72 pixels

per inch. So saving images at a higher resolution results in images that are larger than necessary and take longer to download.

> ## **Summary Images**

 - The <img> element is used to add images to a web page.
 - You must always specify a src attribute to indicate the source of an
   image and an alt attribute to describe the content of an image.
 - You should save images at the size you will be using them on the web
   page and in the appropriate format.
 - Photographs are best saved as JPEGs; illustrations or logos that use
   flat colors are better saved as GIFs.

> # 2. Color in Links:
- How to specify colors  
 - Color terminology and contrast
  - Background color
**Color can really bring your pages to life.**

**How to choose color for any element?**
HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

## Color Values

    <h1 style="background-color:rgb(255, 99, 71);">...</h1>  
    <h1 style="background-color:#ff6347;">...</h1>  
    <h1 style="background-color:hsl(9, 100%, 64%);">...</h1>
Result: 

![image info](./img/img6.png)

