# Difference between document and window object:


| Document objects  | Window objects |
| ------------- | ------------- |
| It is the HTML document that appears in the browser window.  | It is a global object in client-side JavaScript, representing the browser window containing a DOM document  |
| It is the object of window property.  | It is the object of the browser.  |
| It is loaded inside the window.  | It is the first object that is loaded in the browser.  |
| All the tags, elements with attributes in HTML are part of the document.  | Global objects, functions, and variables of JavaScript are members of the window object.  |
| The document is part of BOM (browser object model) and dom (Document object model)  | The window is part of BOM, not DOM.  |
| Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title  | Properties of the window object cannot be accessed by the document object.  |
