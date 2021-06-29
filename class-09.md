# forms

form : HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.

## 'Differnt type to contol the form:

- INPUT ELEMENT: This is the most commonly used element within HTML forms.How an <input> works varies considerably depending on the value of its type attribute, hence the different types are covered in their own separate reference pages. If this attribute is not specified, the default type adopted is text.The available types are as follows: 1. button: A push button with no default behavior. 2. checkbox: A check box allowing single values to be selected/deselected. 3. color: HTML5 A control for specifying a color. A color picker's UI has no required features other.
- TEXT FIeld : Text fields are one line areas that allow the user to input text.Single-line text input controls are created using an <input> element, whose type attribute has a value of text.
- PASSWORD FIELD : You can create a password field by using the <input> element with the type attribute set to the password. But nowadays many form builders are available in the market that provides a password field in the form. It helps you by providing a password field in the form and eases your task and efforts.
- RADIO BUTTONS : Radio buttons are used to let the user select exactly one option from a pre-defined set of options. It is created using an <input> element whose type attribute has a value of radio.
- CHECKBOKES:Checkboxes allows the user to select one or more option from a pre-defined set of options. It is created using an <input> element whose type attribute has a value of checkbox.
- FILE SELECT FIELD : he <input type="file"> defines a file-select field and a "Browse" button for file uploads. To define a file-select field that allows multiple files to be selected, add the "multiple" attribute. Tip: Always add the <label> tag for best accessibility practices.
- SELECT BOX : A select box is a dropdown list of options that allows user to select one or more option from a pull-down list of options. Select box is created using the <select> element and <option> element.The <option> elements within the <select> element define each list item.
- > NOTE: HTML5 introduces a number of new form elements. Some of them are <datalist>, <keygen>, <output>, <progress> and <meter>. In addition to this, there are different input types which we can use with the <input> element. In this section, we are going to look at new form elements one by one.

## Lists, Tables and Forms

- list The CSS list-style-type property is used to define the style of the list item marker: An ordered list starts with the <ol> tag. Each list item starts with the <li> tag. The type attribute of the <ol> tag, defines the type of the list item marker: HTML also supports description lists.The list-style-position property defines where to position the list marker, and it accepts one of two values: inside or outside. These are demonstrated below with the padding removed from the lists and a left red border added.
  ### **list style type**
- Bullet Point Styles = a thick point symbol used to create a top-down list of text to express the start of the item in the list. Bullet points also called as Bullet List in HTML or Word terminology. Even a thick point is used it is called as a bullet.

> bullet poiny symbols:Bullet point uses a thick point as default symbol. But there are diferent alternatives which can be used for bullet point, like :
1 -Thin point
2- Empty point
3 -Square
4 -Grayed point
5 -Arrow
6 -Uppercase Letter
7 -Lowercase Letter
9- Number
  
  > Images for BULLETS = In this article, we have given some list items and the task is to create a list items with image bullets.  This task can be done by using the list-style-image property in CSS.  This property is used to set the image that will be used as the list item marker.
  > osition the maker =The list-style-position property specifies the position of the list-item markers (bullet points).

list-style-position: *outside*; means that the bullet points will be outside the list item.The start of each line of a list item will be aligned vertically.list-style-position, *inside* means that the bullet points will be inside the list item. As it is part of the list item, it will be part of the text and push the text at the start.

- tables: The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells. The HTML tables are created using the <table> tag in which the <tr> tag is used to create table rows and <td> tag is used to create data cells.The cellpadding attribute of HTML table tag is obselete now. It is recommended to use CSS. So let's see the code of CSS. We can specify the HTML table width using the CSS width property. It can be specify in pixels or percentage. We can adjust our table width as per our requirement. Following is the example to display table with width.
  and the A table header is defined with the “th” tag. By default, table headings are bold and centered. A table data/cell is defined with the “td” tag. Adding a border to a HTML Table: A border is set using the CSS border property. If you do not specify a border for the table, it will be displayed without borders.
  
  ![ablecode](https://www.guru99.com/images/image019(1).png)
  
  -forms :An HTML form is a section of a document which contains controls such as text fields, password fields, checkboxes, radio buttons, submit button, menus etc.An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc. .
  
  ![forms](https://image.slidesharecdn.com/formsinhtml5-151129184009-lva1-app6892/95/forms-in-html5-3-638.jpg?cb=1448822487)
  
## EVENTS IN JS

  Events allow JavaScript to detect when a certain action has been performed by the user, e.g. hovering over an element, clicking a link, scrolling the page, resizing the window, dragging an object or any other activity.
  When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

Developers can use these events to execute JavaScript coded responses, which cause buttons to close windows, messages to be displayed to users, data to be validated, and virtually any other type of response imaginable.

Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.
> onclick Event Type : The JavaScript onclick event executes a function when a user clicks a button or another web element. This method is used both inline in an HTML document and in a JavaScript document. When you are coding in JavaScript, it’s common to want to run code when a user interacts with the web page.
> onsubmit Event Type : onsubmit is an event that occurs when you try to submit a form. You can put your form validation against this event type.
> onmouseover and onmouseout: These two event types will help you create nice effects with images or even with text as well. The onmouseover event triggers when you bring your mouse over any element and the onmouseout triggers when you move your mouse out from that elemen.

  ![table code](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events.png)
