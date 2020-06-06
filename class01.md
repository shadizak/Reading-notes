
# HTML5 & CSS

_Introduction_

In this course, you will learn more about HTML and CSS and to create your first web page

**Why HTML?**
1. HTML describes the structure of a web page 
2. HTML is a tags language so every tag describe it's content


## HTML describes tHe Structure of Pages

 To describe the structure of a web page, we add code to the words we want to appear on the page.

```
html>
    <body>
        <h1>
            This is the Main Heading
        </h1>
        <p>
            This text might be an introduction to the rest of
            the page. And if the page is a long one it might
            be split up into several sub-headings.
        <p> 
        <h2>
            This is a Sub-Heading
        </h2>
        <p>
            Many long articles have sub-headings so to help
            you follow the structure of what is being written. There may even be sub-sub-headings (or lower-level headings).
        </p>
        <h2>
            Another Sub-Heading
        </h2>
        <p>
            Here you can see another sub-heading.
        </p> 
    </body>
</html>
```

Each tag in HTML must have a close tag `<p></p>` and every tag can have one or more attribute like if I need to say that this `<p>` language is English  so the tag will be like this
```
<p lang="en-us"> Waleed A. Afifi </p>
```

## body, head & title

#### body

You met the body element
in the first example we created. Everything inside this element is shown inside the main browser window.


#### Head

Before the body element you will often see a head element. This contains information
about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page).
You will usually find a title element inside the head element.


#### Title

The contents of the title element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or
on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).


## How you can create Your first HTML page?

You can use and code editor like VSC, Notepad++, XCode, Atom, etc..
Or you can use the Notepad that installed in you PC the one that came with your Windows OS **Notepad** all you new is open Notepad and copy the code in the top of this page and paste it in Notepad then save the file with extension  _.html_  and that's it.


### HTML Summary

1. HTML pages are text documents.
2. HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
3. Tags are often referred to as elements.
4. Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
5. Opening tags can carry attributes, which tell us more about the content of that element.
6. Attributes require a name and a value.
7. To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.



# Doctypes
Html5 must have Doctypes in the beginning file like below
```
<!DOCTYPE html>
```

**Comment in the HTML**
```
<!-- Comment goes here -->
```

**ID Attribute**

You can add ID for one element only and it can not be repeated like
```
<p id="MYParagraph"></p>
```

**Class Attribute**

Class can be implemented to more than one element
```
<p class="paragraph"></p>
```

**Block element**

Some elements will always appear to start on a new line in the browser window. These are known as block-level elements.
```
<ul>
    <li>Science: 21 Nov - 20 Feb 2010/11</li>
    <li>Architecture: 6 Mar - 15 May 2011</li>
    <li>History: 29 May - 21 Aug 2011</li>
    <li>Religion: 28 Aug - 6 Nov 2011</li>
</ul>
```
Examples of block elements are h1, p, ul, and li.


# HTML layout
![Html Layout](https://www.w3schools.com/html/img_sem_elements.gif)
