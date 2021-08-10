# object Literals

A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.
> What is object in JavaScript?
JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or key) and a value. ... In addition to objects that are predefined in the browser, you can define your own objects.
> How do you create an object in JavaScript?
1 -Define and create a single object, using an object literal.
2 -Define and create a single object, with the keyword new .
3 -Define an object constructor, and then create objects of the constructed type.
> You can access the properties of an object in JavaScript in 3 ways:
Dot property accessor: object.property
Square brackets property access: object['property']
Object destructuring: const { property } = object

## Document Object Model

The Document Object Model (DOM) connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. Usually, that means JavaScript, although modeling HTML, SVG, or XML documents as objects are not part of the core JavaScript language, as such.
> THE DOM TREE IS A MODEL OF A WEB PAGE:A DOM tree starts from the topmost element which is html element and branches out as per the occurrence and nesting of HTML elements in the document. Whenever an HTML element is found, it creates a DOM node (Node) object from its respective class (constructor function).

- Dome node  interface is an abstract base class upon which many other DOM API objects are based, thus letting those object types to be used similarly and often interchangeably. As an abstract class, there is no such thing as a plain Node object.
- Element node describe the structure of an html page like heading to access the DOM tree, you start by looking for
elements. Once you find the element you want, then you can access its text and attribute nodes if you
want to.
- attribute node:Attribute nodes are not children of the element thar carries them; they are part of that element. Once
you access an element, there are specific JavaScript methods and properties to read or change that element's attributes
- text node : All viewable HTML text in a page (except text in form elements or custom embedded objects) is in text nodes. ... For example, a div is an ELEMENT node which can contain child nodes. Those child nodes can be other ELEMENT nodes or they can be TEXT nodes or COMMENT nodes or other types of node.

![dom](https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-the-dom-tree/Image_6_DomTree.png)

## WORKING WITH THE DOM TREE

You don't have to do anything special to begin using the DOM. Different browsers have different implementations of the DOM, and these implementations exhibit varying degrees of conformance to the actual DOM standard (a subject we try to avoid in this documentation), but every web browser uses some document object model to make web pages accessible via JavaScript.

When you create a script–whether it's inline in a <script> element or included in the web page by means of a script loading instruction–you can immediately begin using the API for the document or window elements to manipulate the document itself or to get at the children of that document, which are the various elements in the web page. Your DOM programming may be something as simple as the following, which displays an alert message by using the alert() function from the window object, or it may use more sophisticated DOM methods to actually create new content, as in the longer example below.
1 -you can select dom element by id: The id selector uses the id attribute of an HTML element to select a specific element. The id of an element is unique within a page, so the id selector is used to select one unique element! To select an element with a specific id, write a hash (#) character, followed by the id of the element.
2 - select dom element by class: The getElementsByClassName method of Document interface returns an array-like object of all child elements which have all of the given class name(s). When called on the document object, the complete document is searched, including the root node. You may also call getElementsByClassName() on any element; it will return only elements which are descendants of the specified root element with the given class name(s)

### nodelist

 NodeList objects are collections of nodes, usually returned by properties such as Node. childNodes and methods such as document. querySelectorAll() . Although NodeList is not an Array , it is possible to iterate over it with forEach() . It can also be converted to a real Array using Array.
 A NodeList is a collection of document nodes. A NodeList and an HTML collection is very much the same thing. Both an HTMLCollection object and a NodeList object is an array-like list (collection) of objects.

### DOM interfaces

 This guide is about the objects and the actual things you can use to manipulate the DOM hierarchy. There are many points where understanding how these work can be confusing. For example, the object representing the HTML form element gets its name property from the HTMLFormElement interface but its className property from the HTMLElement interface. In both cases, the property you want is in that form object.

But the relationship between objects and the interfaces that they implement in the DOM can be confusing, and so this section attempts to say a little something about the actual interfaces in the DOM specification and how they are made available.

> Interfaces and Objects
Many objects borrow from several different interfaces. The table object, for example, implements a specialized HTMLTableElement interface, which includes such methods as createCaption and insertRow. But since it's also an HTML element, table implements the Element interface described in the DOM Element Reference chapter. And finally, since an HTML element is also, as far as the DOM is concerned, a node in the tree of nodes that make up the object model for an HTML or XML page, the table object also implements the more basic Node interface, from which Element derives.

When you get a reference to a table object, as in the following example, you routinely use all three of these interfaces interchangeably on the object, perhaps without knowing it.
> Core Interfaces in the DOM
This section lists some of the most commonly-used interfaces in the DOM. The idea is not to describe what these APIs do here but to give you an idea of the sorts of methods and properties you will see very often as you use the DOM. These common APIs are used in the longer examples in the DOM Examples chapter at the end of this book.

The document and window objects are the objects whose interfaces you generally use most often in DOM programming. In simple terms, the window object represents something like the browser, and the document object is the root of the document itself. Element inherits from the generic Node interface, and together these two interfaces provide many of the methods and properties you use on individual elements. These elements may also have specific interfaces for dealing with the kind of data those elements hold, as in the table object example in the previous section.

![domtree](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)

## Testing the dom

This document provides samples for every interface that you can use in your own web development. In some cases, the samples are complete HTML pages, with the DOM access in a <script> element, the interface (e.g, buttons) necessary to fire up the script in a form, and the HTML elements upon which the DOM operates listed as well. When this is the case, you can cut and paste the example into a new HTML document, save it, and run the example from the browser.

There are some cases, however, when the examples are more concise. To run examples that only demonstrate the basic relationship of the interface to the HTML elements, you may want to set up a test page in which interfaces can be easily accessed from scripts. The following very simple web page provides a <script> element in the header in which you can place functions that test the interface, a few HTML elements with attributes that you can retrieve, set, or otherwise manipulate, and the web user interface necessary to call those functions from the browser.

You can use this test page or create a similar one to test the DOM interfaces you are interested in and see how they work on the browser platform. You can update the contents of the test() function as needed, create more buttons, or add elements as necessary.
