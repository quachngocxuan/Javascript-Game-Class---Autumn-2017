# The 1st session lecture notes

**Objectives:**
- Install a webpage editor
- Introduction about web technology (HTML, CSS, Javascript)
- How to create a new web page
- Structure of a web page
- Structure of a HTML tag
- Some common tags
- Some style attributes
- How to layout a web page by absolute positioning
- Exercises

## Install a webpage editor
In this course, we'll an HTML editor to edit web pages. Students can choose one of these editors: Notepad++, Sublime, Brackets

## Introduction about web technology
- A **web page** is a document which is rendered by a web browser (Chrome, Firefox, IE...)
- A **web browser** is a software to display web pages
- The **web technology** generally is based on three components: HTML - to structure contents of a web page, CSS - to decorate a web page, Javascript - to handle interaction on a web page

## How to create a new web page
- Open a web editor and create a new file, save as a file ended with .html (ex. index.html)
- Input some text paragraphs
- Save the file
- Back to the folder containing the created file, double click on it to open the web page on a web browser

## Structure of a web page
A web page is allways contained between
```html
<html>
</html>
```
Content which is displayed on a web page is presented between ```<body></body>```
```html
<html>
  <body>
    Content here
  </body>
</html>
```

## Structure of a HTML tag
Generally, each content on a web page is described by a **HTML tag**. When using a HTML tag, content is placed between an **open tag** and a **closing tag**:
```<tag_name>content</tag_name>```

Ex: 
```html
<p>Hello HTML</p>
```

A HTML tag can specify some attributes to change its styles: font, font-size, color, width, height...

Ex:
```html
<p text-align="center">Hello HTML</p>
```

Each tag has its own attributes. See it on a reference document (W3schools.com).

## Some common tags
There are some common tags you should be familiar:
- **\<img>**: represents an image
- **\<a>**: represents a hyperlink
- **\<p>**: represents a paragraph
- **\<iframe>**: embed content from another web page (ex: YouTube)
- **\<div>**: represents a content container

## Some tag attributes
- **text-align**: to set alignment of text (\<p>)
- **width**: to set width of a content container
- **height**: to set height of a content container
- **padding**: to set spacing between content and border
- **color**: to set color of text

## How to layout a web page by absolute positioning
To position a content on a web page absolutely you should follow two steps
1. Place content on a container tag (\<div>) and set its identifier by the attribute **id**
```html
<div id="image1"><img src="image_URL" /></div>
```
2. Put a style definition for it between ```<head></head>```
```HTML
<head>
  <style>
    div#image1 {
      position: absolute;
      left: 10px;
      border:5px solid green;
      text-align:center;
      padding: 50px;
    }
  </style>
 </head>
 ```
 - **position**: set as absolute to position the container absolutely
 - **left, right, bottom, top**: to align the container
 - **border**: to set border of the container
 - **text-align**: to align content in the container
 - **padding**: to set space between content and border
 
## Exercises
- Create a web page with any content: text, images, hyperlinks, Youtube videos
- Create a web page with 4 box on each corner of the web page
