# day-03



Difference between window, document and screen in JavaScript:

Window:
          *The window object is the topmost object of the DOM hierarchy. It is the root level element in any web page.
* It represents a browser window or frame that displays the contents of the webpage. 

*The window object is supported by all browsers.

*Whenever a window appears on the screen to display the contents of the document, the window object is created.
* It is the very first object that is loaded in the browser. It is the object of the browser
*Global objects, functions, and variables of JavaScript are members of the window object. All the global variables are defined on the window object.
* The window is part of BOM (browser object model), not DOM (Document object model).
*We can access the window from the window only. i.e. window.window. Properties of the window object cannot be accessed by the document object.

syntax:
            window.propertyname;

Example:
window.innerHeight : will return the height of the content area of the browser.

Screen:
	*Screen is a small information object about physical screen dimensions .
* It can be used to display screen width, height, colorDepth, pixelDepth etc. 
*It is not mandatory to write window prefix with screen object. It can be written without window prefix.
*The screen  have an properties like width, height, colorDepth, pixelDepth, etc.
syntax:
screen.propertyname;

Document Object: 
*The document object represent a web page that is loaded in the browser. 
*By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. 
*The document object can be accessed with a window.document or just document.
* It is loaded inside the window. It is the object of window property. All the tags, elements with attributes in HTML are part of the document.
*We can access the document from a window using the window. Document.
*The document is part of BOM (browser object model) and dom (Document object model).
*Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title .

Syntax:
            document.propertyname;

Example:  
 document.title :  will return the title of the document


