# Reading-09

Whenever you want to collect information from visitors you will need a form, which lives inside ana <form> element.
    Adding Text :
        Text input
        Password input
        Text area

    Making Choices:
        Radio buttons
        Checkboxes
        Dropdown boxes

    Submitting Forms:
        File upload
        Information from a form is sent in name/value pairs.
        Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

HTML5 introduces new form elements that make it easier for visitors to fill in forms.

## Chapter 14: “Lists, Tables & Forms” (pp.330-357)

**Bullet-point Styles**

List style type can be used on rules that apply to the <ol>, <ul>, and <li> elements.

List style images can specify an image to act as a bullet point using the list-style-image property.

List style position lists are indented into the page by default and the list-style- position property indicates whether the marker should appear on the inside or the outside of the box containing the main points.

This property can take one of two values, inside or outside.

Shorthand List style, as with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called list-style, and it allows you to express

the markers' style, image and position properties in any order.

**Table Properties**

Width to set the width of the table

Padding to set the space between the border of each table cell and its content

Text-transform to convert the content of the table headers to uppercase

Letter-spacing, font-size to add additional styling to the content of the table headers

Border-top, Border-bottom to set borders above and below the table headers

Text-Align to align the writing to the left of some table cells and to the right of the others

Background-color to change the background color of the alternating table rows

Hover to highlight a table row when a user's mouse goes over it

Border On Empty Cells

Since browsers treat empty cells in different ways, if you want to explicitly show or hide borders on any empty cells then you should use this property. It can take one of three values:

Show - This shows the borders of any empty cells.
Hide - This hides the borders of any empty cells.
Inherit - If you have one table nested inside another, the inherit value instructs the table cells to obey the rules of the containing table.

## Web Developer Toolbar

A helpful extension for Firefox and Chrome provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML.

*www.chrispederick.com/ work/web-developer*

Outlines - When you hover over an element, a red outline will be drawn around it, showing you how much space the element takes up.

Structure - While you are hovering over an element, the structure will be shown at the top of the window. Here you can see the <li> element has a class of completed, inside a <ul> with a class called to-do. The list is inside a <div> element with an id of page, and this sits inside the <body> and <html> elements. This can be very helpful when writing CSS selectors to help you target the right element.

CSS Styles - When hovering over an element, click with your mouse to display the CSS. You will be shown the rules that apply to that element (and the line they are on). Above the rules, you can see the name of the style sheet (and the path to it). This helps check which styles are being applied to an element. You can use it on code for your own site or when you want to see what styles someone else is using on their site.

In addition to the CSS properties covered in other chapters that work with the contents of all elements, several others are specifically used to control the appearance of lists, tables, and forms.

List markers can be given different appearances using the list-style-type and list-style-image properties.

Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.

Forms are easier to use if the form controls are vertically aligned using CSS.
Forms benefit from styles that make them feel more interactive.

## Chapter 6: “Events” (pp.243-292)

Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).

Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.

You can use event delegation to monitor for events that happen on all of the children of an element.

The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.