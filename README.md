# css
CSS, which stands for Cascading Style Sheets, is a stylesheet language used to describe the presentation and formatting of web documents written in HTML or XML. It allows you to control the layout, design, and visual appearance of web pages. CSS works by selecting HTML elements and applying styles to them. Styles can include properties like color, font size, margins, padding, and more.  
the web page will look so basic without css or style sheet  
css is a optional converts off loking HTML into a  beautiful and responsive website  
*basic example of css*  
HTML(index.html)
```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a simple example of CSS.</p>
    <p class="important">This is an important paragraph.</p>
</body>
</html>
```
CSS(styles.css)
```css
/* This is a CSS comment */
h1 {
    color: blue;
    font-size: 24px;
}

p {
    font-family: Arial, sans-serif;
    line-height: 1.5;
}

.important {
    font-weight: bold;
    color: red;
}
```
--In this example, we have an HTML document (index.html) and a separate CSS file (styles.css) linked to it.  
##DOM
The DOM, or Document Object Model, is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content dynamically.    
##html id and class atributes  
In HTML, both the id and class attributes are used to specify attributes for elements, but they serve different purposes and have distinct characteristics:  
*1)* id Attribute:  

The id attribute is used to uniquely identify a single HTML element on a web page. Each id value within a page must be unique; no two elements should share the same id.  
It is often used when you want to select and manipulate a specific element using JavaScript or when you need to create anchor links that jump to a particular element on the page.  

*2)*class Attribute:  

The class attribute is used to assign one or more class names to an HTML element. Multiple elements on a page can share the same class name.  
It is typically used for styling purposes with CSS or for selecting and applying styles to groups of elements using JavaScript.  
You can apply the same class to multiple elements, allowing you to style or manipulate them collectively.  
Class names can contain letters, numbers, hyphens, and underscore  
